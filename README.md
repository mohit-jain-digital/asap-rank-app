# ASAP-Rank (your own copy)

This runs ASAP-Rank on **your own Cloudflare account**. Your pages, SEO changes, popups, chatbot and contacts are stored in your own database. They are never sent to ASAP-Rank.

The only thing your copy sends to the ASAP-Rank licence server is your licence key and your app address, each time someone logs in, to ask whether your subscription is active.

## Deploy

1. Create your ASAP-Rank account and copy your licence key (More, Account).
2. Press the Deploy to Cloudflare button in the setup guide, or open
   `https://deploy.workers.cloudflare.com/?url=THIS_REPO_URL`
3. Enter `LICENSE_KEY` and `SECRET` when asked. Deploy.
4. Open your app address and create your admin login with the same email you used to buy.

## Optional settings (Cloudflare, Workers, your app, Settings, Variables)

| Name | What it does |
|---|---|
| BREVO_KEY or RESEND_KEY | Sends email (sign-in help, CRM messages, drips) |
| MAIL_FROM | Sender, for example `Your name <you@yourdomain.com>` |
| GEMINI_KEY | The AI that writes suggestions and powers the chatbot |
| PSI_KEY | Google PageSpeed key for speed tests |
| APP_URL | Only if you use your own domain |

## Updating

When a new version is published, open your GitHub copy and press **Sync fork**. Cloudflare deploys it by itself.

## Help

Open an issue in this repository and say which step you are on. Never paste your licence key, SECRET or any API key. If we ask, add us as a collaborator on your copy.

## Free plan limits

Cloudflare's free plan allows 100,000 requests a day and 5 GB of database storage for you alone, not shared with other customers.
