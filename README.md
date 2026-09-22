# SocialFaktory for Gemini CLI

Run a brand's social media from the terminal. This extension connects Gemini CLI to
[SocialFaktory](https://www.socialfaktory.com), which writes posts, generates video, schedules
and publishes on TikTok, Instagram, YouTube, X, LinkedIn, Facebook and Pinterest, and reads
the metrics back.

## Install

```bash
gemini extensions install https://github.com/adifsgaid/socialfaktory-gemini-extension
```

The first call opens a SocialFaktory consent screen in your browser. There is no token to
paste and no client id to create: the CLI registers itself and signs in through OAuth.

## What the consent screen asks

1. Sign in to SocialFaktory if you are not already.
2. Tick what the CLI may do. **Read** sees your brands, media and posts. **Generate** creates
   video and text on your credits. **Publish** schedules and sends posts on your channels,
   so leave it off until you trust the brief.
3. Pin the connection to one brand, or leave it on all brands.
4. Choose how long the connection lasts: 30, 60 or 90 days.
5. Set a monthly credit cap, or leave it empty for none, and press Connect. Reading is free
   either way.

Disconnect it any time from Settings, API tokens. The CLI loses access immediately.

## What it can do

Twenty tools: list brands, channels and formats, quote a video before paying for it,
generate video and text, upload your own file, compose and schedule posts, send them,
withdraw them, and read how they performed. Reading is free. Generating spends credits, and
the CLI is told to quote first and ask you.

Cloning a video from a link, and generating still images or carousels, are not available
through an agent yet.

## Try

- "List my brands and the channels each one has connected."
- "Quote a 15 second product video for the Nordlys brand and show me the price."
- "Write three X post variants about our autumn launch, in the brand voice."
- "Create a draft post for Instagram from the last finished video, scheduled for Friday 9am."

## Documentation and support

Reference: https://www.socialfaktory.com/docs/mcp. Support: hello@socialfaktory.com, answered
within one business day.
