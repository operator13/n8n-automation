# n8n-automation
## Workflow List

## AI Agent Crypto Quant Workflow Overview

This workflow automates crypto quant analysis and reporting using n8n, integrating multiple data sources and AI for real-time insights. It is triggered by a Slack command and performs multi-step processing to deliver actionable intelligence directly to Slack.

### Workflow Steps

- **Slack Trigger:**  
  The workflow starts when a specific command/message is received in Slack.

- **Data Retrieval & Processing:**  
  - Executes a custom code block to preprocess the request.
  - Fetches cryptocurrency data from multiple APIs using several HTTP Request nodes.
  - Edits and standardizes API responses for downstream processing.

- **Data Merging & Analysis:**  
  - Merges data streams into a consolidated dataset.
  - Performs sentiment analysis on news or relevant text data to gauge market sentiment.
  - Combines all JSON data for unified processing.

- **AI Agent Analysis:**  
  - Sends the merged and sentiment-enriched data to an OpenAI-based AI Agent.
  - The AI Agent generates insights, summaries, or recommendations based on the input data.

- **Reporting:**  
  - Formats the AI’s output.
  - Sends the final analysis back to the original Slack channel as a response.

### Features

- Multi-source crypto data aggregation
- Automated sentiment analysis
- Integrated AI agent for advanced insights
- Slack-based trigger and reporting for seamless team communication

**Ideal for:**  
Teams needing automated, AI-driven crypto market analysis delivered directly into Slack.

---

- **AI_Agent_Crypto_Quant.json**  
  Automates crypto quant analysis using AI agents and various data sources.

## How to Use

1. Download the desired `.json` workflow file.
2. In your n8n instance, click "Import" and upload the JSON file.
3. Configure any required credentials or environment variables.
4. Activate the workflow.
