🎯 MC Name Sniper

A powerful Minecraft username sniper tool with auto-claim functionality. Features dual modes (Spam/Monitor), multi-name support, token validation, and intelligent rate limit handling. Interactive CLI with color-coded output and graceful shutdown.
⚠️ Disclaimer

For educational purposes only. Using automated tools may violate Minecraft's Terms of Service. Use at your own risk. Only use on usernames you have legitimate rights to claim.
✨ Features

    Dual Sniper Modes: Spam (instant claims) or Monitor (availability checks)

    Multi-Name Support: Target multiple usernames simultaneously

    Token Validation: Automatically verifies Microsoft Bearer tokens

    Rate Limit Handling: Intelligent retry logic with appropriate delays

    Color-Coded Console: Easy-to-read output with ANSI colors

    Graceful Shutdown: Ctrl+C handling with cleanup

📋 Prerequisites

    Node.js (v14 or higher)

    Microsoft account with Minecraft Java Edition

    Valid Microsoft Bearer token

🚀 Installation
bash

git clone https://github.com/yourusername/mc-name-sniper.git
cd mc-name-sniper
npm install

🔧 Usage
bash

node sniper.js

Follow the interactive prompts for target usernames, Bearer token, and sniper mode selection.
Getting Your Bearer Token

    Log into minecraft.net

    Open Developer Tools (F12) → Network tab

    Find a request to api.minecraftservices.com

    Copy the Authorization header value (without "Bearer " prefix)
