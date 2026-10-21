[← Selected work](../README.md)

# Pravkin

**One small change. One simple conversation.**

A date needs updating. A number is wrong. A page needs changing. Pravkin brings everyday PDF edits into a Telegram conversation: send the document, describe what you want and review the result before receiving the edited file.

[Open the bot →](https://t.me/PravkinPDF_bot) · [View the visual case →](https://yaroslavkonevmsk-max.github.io/yaroslavkonevmsk-max/pravkin.html)

![The real public Telegram entry page for Pravkin](../assets/pravkin-telegram.png)

## The experience

The user uploads a PDF and describes the requested edit in ordinary language. The bot turns that instruction into a reviewable change, shows a preview and asks for approval before delivering the final file. The conversation gives each step a clear place: upload, describe, check and confirm.

The screenshot above is the live public bot entry page. The original project identity appears below.

<img src="../assets/pravkin-logo.png" width="240" alt="Pravkin's original document and pencil logo">

## What was built

- A Telegram conversation flow for PDF uploads, editing instructions and file delivery.
- Natural-language interpretation of requested document changes.
- Preview and explicit approval before the user receives the final PDF.
- Upload limits, controlled processing and short-lived document storage.
- Consent before document text is sent for AI analysis.

The implementation uses Python, aiogram, PostgreSQL and DeepSeek for interpreting editing requests.

## Current scope

Pravkin is a limited PDF beta. File and usage limits apply, complex layouts may be unsupported, and the user checks the preview before confirming. Current availability is shown in the bot.

[Discuss a Telegram workflow →](https://t.me/YasikKonco) · [Back to selected work](../README.md)
