# ChatGPT for Slack Bot

This is a simple chatbot that uses the  package to respond to messages in Slack. It is designed to be used with the Slack Events API, and it listens for app_mention events, which are triggered when a user mentions the bot in a Slack channel.

Installation
============
1. Clone this repository.
  ```
  git clone https://github.com/thomgonzalez/GPTSlackBot.git
  ```
2. Install the required packages.
  ```
   pip install -r requirements.txt
  ```
3. Edit the .app.env file in the root directory of the project and add your Slack and OpenAI API keys.
  ```
  export SLACK_BOT_TOKEN=slack_bot_token
  export SLACK_APP_TOKEN=slack_app_token
  export OPENAI_API_KEY=you_openai_api_key
  ```
