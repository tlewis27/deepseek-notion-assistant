# DeepSeek Notion Assistant

A beautiful chat interface that embeds directly into Notion, powered by DeepSeek AI.

## Quick Start

1. **Get API Keys:**
   - Notion: https://www.notion.so/my-integrations
   - DeepSeek: https://platform.deepseek.com/api

2. **Deploy:**
   - Click "Deploy" button below
   - Add your API keys in environment variables
   - Copy your deployment URL

3. **Embed in Notion:**
   - Type `/embed` in any Notion page
   - Paste your deployment URL
   - Resize as needed

## Local Development

```bash
# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys

# Run the app
python app.py
