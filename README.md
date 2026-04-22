🔒 CryptoShield
This encryption tool that generates self-decrypting HTML files. Encrypt any file, send it to anyone — they just open it in a browser and enter the password to get the original file back. No software installation needed.

⚡ How It Works
Upload any file (image, PDF, document, ZIP — anything)
Set a password and configure protection settings
Click Encrypt → generates a single .html file
Send that HTML file to anyone (WhatsApp, email, AirDrop, USB — any method)
Recipient opens it in any browser → enters password → downloads the original file
100% client-side. Nothing is ever uploaded to any server. Everything runs in your browser using the native Web Crypto API.

ENcryption format:
┌─────────────┬────────────┬──────────────────┬────────────┐
│ Salt │ IV │ Ciphertext │ Auth Tag │
│ 16 bytes │ 12 bytes │ Variable length │ 16 bytes │
└─────────────┴────────────┴──────────────────┴────────────┘

Access it at : https://cryptoshield.space.z.ai/
