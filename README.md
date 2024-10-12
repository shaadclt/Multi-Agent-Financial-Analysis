# Financial Analysis using Multi-agent system
This project utilizes a multi-agent system powered by crewAI to monitor, analyze, and strategize in the financial markets, specifically focusing on stock trading. Each agent in the system specializes in a unique aspect of trading, working together to provide comprehensive insights and actionable strategies.

## Overview
The Multi-agent Financial Analysis system is designed to assist in the following tasks:

1. **Data Analysis**: Continuously monitor and analyze market data to identify trends and predict market movements.
2. **Trading Strategy Development**: Create and refine trading strategies based on insights from market analysis and user-defined risk tolerance.
3. **Trade Execution Planning**: Suggest optimal trade execution strategies by evaluating the timing, price, and logistics of potential trades.
4. **Risk Management**: Evaluate and provide insights on the risks associated with potential trading activities.

## System Architecture
### Agents
#### Data Analyst Agent:

- **Role**: Monitor and analyze market data in real-time to identify trends and predict market movements.
- **Goal**: Provide crucial insights for informed trading decisions.
  
#### Trading Strategy Developer Agent:

- **Role**: Develop and test various trading strategies based on insights from the Data Analyst Agent.
- **Goal**: Devise profitable and risk-averse trading strategies.

#### Trade Advisor Agent:

- **Role**: Suggest optimal trade execution strategies based on approved trading strategies.
- **Goal**: Ensure efficient and timely trade execution.

#### Risk Advisor Agent:

- **Role**: Evaluate and provide insights on the risks associated with potential trading activities.
- **Goal**: Align trading activities with the firm’s risk tolerance.

### Tasks
#### Data Analysis Task:

- **Description**: Continuously monitor and analyze market data for a selected stock.
- **Output**: Insights and alerts about significant market opportunities or threats.

#### Strategy Development Task:

- **Description**: Develop and refine trading strategies based on insights from the Data Analyst and user-defined risk tolerance.
- **Output**: A set of potential trading strategies that align with the user's risk tolerance.

#### Execution Planning Task:

- **Description**: Analyze approved trading strategies to determine the best execution methods for the selected stock.
- **Output**: Detailed execution plans suggesting how and when to execute trades.

#### Risk Assessment Task:

- **Description**: Evaluate the risks associated with the proposed trading strategies and execution plans.
- **Output**: A comprehensive risk analysis report detailing potential risks and mitigation recommendations.

## License
This project is licensed under the [MIT License](LICENSE.txt).
