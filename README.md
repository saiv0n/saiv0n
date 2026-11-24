## hey, i'm umut

I write Rust most days, and Python, TypeScript or Svelte when a project needs it. I like small tools that do one thing properly.

I also build three kinds of things for businesses: scrapers that put a shop's products and prices into a spreadsheet, support chatbots that answer from your own help pages, and automations that sort incoming messages and leads. Each project below runs, has tests, and shows real output in its README, so you can check my work before we talk.

### [price-watch](https://github.com/saiv0n/price-watch)

Pulls product listings from online shops into Excel, CSV or Google Sheets, follows each product page for the details, keeps a price history and messages you on Slack, Discord or Telegram when a price drops. Shopify stores need no setup at all. It runs every day on GitHub Actions without a server.

### [askbase](https://github.com/saiv0n/askbase)

A chat widget for your website that answers customers from your own documents and shows which page every answer came from. When the docs don't have the answer it says so instead of making one up, and it keeps a list of the questions your docs couldn't answer. One script tag to add, works with Claude, OpenAI, Gemini or a model on your own server.

### [n8n-ai-triage](https://github.com/saiv0n/n8n-ai-triage)

An n8n workflow that reads contact form and inbox messages, sorts them into leads, support, partnerships and spam, scores leads from 0 to 100 and drafts a reply in the sender's language. Checked against twelve test messages in three languages, including one that tries to trick the model.

### things i made for myself

<a href="https://github.com/saiv0n/pinna">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/saiv0n/pinna/main/docs/img/card-dark.png">
    <img src="https://raw.githubusercontent.com/saiv0n/pinna/main/docs/img/card-light.png" width="420" alt="Pinna">
  </picture>
</a>

[pinna](https://github.com/saiv0n/pinna): My AirPods worked on Linux, but only as a plain headset. No battery, no noise control, no settings. Pinna fixes that: it talks to the buds the way an iPhone does and puts everything in a native Qt app, with a tray icon, a card when you open the case, and a mic that doesn't turn your calls into a phone line. Rust underneath. Windows and Android are next.

[trawl](https://github.com/saiv0n/trawl): A download manager I started because I didn't like the ones out there. Multiple connections per file, downloads that survive a crash, video from most sites through yt-dlp, and a browser extension that takes over your downloads. Rust and Tauri, Svelte for the UI.

### working with me

If you need something like the projects above, or a fix to a scraper or automation you already have, open an issue on any of these repos with a short description and I'll get back to you within a day.
