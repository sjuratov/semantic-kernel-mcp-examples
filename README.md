This repo is insipred by https://developers.onwardplatforms.com/blog/2025/04/14/using-mcp-servers-with-semantic-kernel-in-python/code/README

Important changes from original repo:
- Using Azure OpenAI instead of OpenAI
- Using mcp instead of mcp-python-sdk in requirements.txt
- .env file has following environment variables

AZURE_OPENAI_CHAT_DEPLOYMENT_NAME="gpt-4o-mini"
AZURE_OPENAI_ENDPOINT="https://xyz.openai.azure.com/"
AZURE_OPENAI_API_KEY="2N4..."