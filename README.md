# 48-Hour Telegram Bot Runner

This repository template allows you to run your Telegram bot script automatically every 48 hours using GitHub Actions, without needing a VPS.

## How to Use:

1. **Fork this repository** to your own GitHub account.

2. **Add your script** to the root of the repository.
   - If it's a Python bot, add your script as `your_script.py`.
   - If it's a Node.js bot, add your script as `your_script.js`.

3. **Optional: Add dependencies**:
   - For Python: Add a `requirements.txt` file with all your dependencies.
   - For Node.js: Add a `package.json` file.

4. **Set up environment variables**:
   - Create a `.env` file at the root of the repository. You can use the provided `.env.example` as a template. Add any API keys, tokens, or secrets your bot needs.

5. **Automatic Scheduling**:
   - Your script will automatically start every 48 hours and run for 48 hours.
   - You do not need to restart it manually.

6. **Manual Run**:
   - If you want to test or run your bot manually, go to the **Actions** tab in your GitHub repository and click the **Run workflow** button.

## Example .env file:

TELEGRAM_TOKEN=your_telegram_bot_token
API_KEY=your_api_key
