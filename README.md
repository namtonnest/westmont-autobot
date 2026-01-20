# Toronto Auto Sales - AI Inventory Bot

An intelligent car inventory chatbot powered by LLM (Large Language Model) AI.

## Features

- 🤖 **AI-Powered Conversations** - Natural language understanding
- 🔍 **Smart Search** - Multi-criteria filtering
- 📊 **Vehicle Comparisons** - Detailed side-by-side analysis
- 💡 **Intelligent Recommendations** - Personalized suggestions
- ⚡ **Real-time Responses** - Instant results

## Quick Setup (Enable AI)

1. **Copy the config template:**
   ```bash
   copy config.template.js config.js
   ```

2. **Get a FREE Groq API Key:**
   - Visit: https://console.groq.com
   - Sign up (free)
   - Create an API key

3. **Edit `config.js`:**
   ```javascript
   const API_CONFIG = {
       groqApiKey: 'your-api-key-here',  // Paste your key
       enableByDefault: true              // Enable AI
   };
   ```

4. **Open `index.html` in your browser** and enjoy AI-powered conversations!

## Supported AI Providers

- **Groq** (Recommended) - FREE & Fast
- OpenAI (GPT-3.5/4)
- Anthropic (Claude)
- Google Gemini

## Usage Examples

- "I want a reliable family SUV under 15k"
- "Show me something with panoramic sunroof"
- "What's the best Audi you have?"
- "Compare your top 2 SUVs"
- "Not interested in Hyundai, show alternatives"

## Tech Stack

- Pure HTML/CSS/JavaScript
- LLM API Integration
- LocalStorage for configuration
- No backend required

## License

MIT License - Feel free to use and modify!
