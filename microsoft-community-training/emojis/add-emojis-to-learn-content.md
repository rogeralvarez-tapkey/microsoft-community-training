---
title: Add unicode emoji icons to Learn content
description: Overview and steps for adding tested unicode emoji icons to Learn content.
author: megan-nesbitt
ms.author: v-mnesbitt
ms.date: 01/12/2023
ms.prod: non-product-specific
ms.topic: contributor-guide
ms.custom: internal-contributor-guide
#Customer intent: As a new content developer or creator, I need to know what unicode emoji icons I can add to my Learn content that will render correctly on the Learn platform and with Accessibility screen reader tools.
#Acrolinx: As of 1/27/23, the Acrolinx score for this article is 94.
---
# Add unicode emoji icons to Learn content

[!INCLUDE [in-review](../includes/in-review.md)]

This article explains how to add emojis to Learn content.

## Overview

- You can use emoji icons in Learn content to provide more context and value.
- You shouldn't add emojis solely for fun.
- Place emojis directly into the Markdown file. This means:
    - **Don't** use the Learn custom `:::image:::` extension with emojis.
    - **Don't** include a file path with emojis.
- Accessibility screen readers can read the emojis in this article correctly. You **don't** need to include alt text with emojis.

## Tested emojis

The following emojis have been tested and confirmed to render correctly with Learn content, PDFs, and Accessibility screen readers.

|Category|Options|
|--------|-------|
|Charts, Notebooks, Paper|✉️ 📧 📥 📤 ✉️ 📨 📄 📃📑 📊 📈 📉 📜 📋 📁 📂 📕 📗 📘 📙 📓 📔 📒 📰 📝 📝 📖 📚 🔖|
|Electronics, Tools|💿 📀 💽 💾 🎮 📷 📹 🎥 💻 📺 📱 📳 📴 📲 ☎️ ☎️ 📞 📟 📠 📻 📇 ⏰ ⌚ 🕓 🕞 🕙 📡 📼 🔬🔭 🔒 🔏 🔓 🔐 🔑 💡 🔦 🔧 🔩 🔨 ✂️ ✒️✏️🔗 📐📏 📎 📌 🔌 🔋 📣 📢 ⌛ ⏳ 🔍🔉 🔈|
|Hand Gestures|👍 👎 ☝️ 👇 👈 👉|
|Numbers, Signs, Symbols|1️⃣ 2️⃣ 3️⃣ 4️⃣ 5️⃣ 6️⃣ 7️⃣ 8️⃣ 9️⃣ 🔟 🔢 0️⃣ #️⃣ 🔣 ◀️ ⬇️ ▶️ ⬅️ 🔠 🔡 🔤 ↘️ ➡️ ⬆️ ↖️ ⏬ ⏫ 🔽 ⤵️ ⤴️ ↩️ ↪️  ↕️ 🔼 🔃 🔄 ⏪ ⏩ ℹ️ 🆗 🔀 🔁 🔂 🆕 🔝 🆙 ☑️ 🎦 📶 🔚 🔙 🔛 🔜 🅿️ ♿ 🚾 ➿ ↔️ ↙️ ↗️ Ⓜ️ 🆔 🚫 ⛔ ✳️ ❇️ ✴️ 🆚 💹 ❎ ❗ ❓ ❕ ❔ ⁉️ ❌ ❗ ‼️ ⭕ ✖️ ➕ ➖ ➗ ✔️ 🔕 🔇 💱 ♻️ 💲 ➰ 〽️|
|Places|🏠 🏡 🏫 🏢 🏣 🏥 🏦 🏪 🏨 💒 ⛪ 🏬 🏤 🌇 🌆 🌐 🌑 🌒 🌓 🌔 🌕 🌖 🌗 🌘 🌍 🌎 🌏|
|Shapes|⚫ ⚪ 🔴 🔵 🔘 🔷 🔶 🔹 🔺 ⬛ ⬜ ♠️ ♥️ ♣️ ♦️ ▪️ ▫️ ◾ ◽ ◼️ ◻️ • ✅ 🔲 🔳 ⭐ 💎 💠 💮 ✨ 🌟 💫 💥 💥 💢 🔆 🔅|
|Miscellaneous|😊 📆 📅 🚦 🚥 🏁 🚩 ⚠️ 🚧 📛 🎨 🎤 🎧 🎬 👓 🎯 🔔 🎉 🎈 🎓 🎲 💯 🏆 📮 📫 📪 📬 📭 📦 🚀 🚇 ✈️ 🌠|

## Add an emoji to Learn content

1. Locate an emoji that matches your intent in the table above.

1. Copy (**Ctrl+C**) and Paste (**Ctrl+V**) the emoji directly into your Markdown file.

   :::image type="content" source="media/add-emojis-to-learn-content/paste-emoji-into-markdown.png" alt-text="Screenshot showing example of pasting an emoji directly into a Markdown file.":::

   - Place the actual emoji into your file, instead of entering the encoded HTML for it. This makes it easier to see and read in Markdown.
   - You can also use **Windows key+period key** to open the Windows emoji menu and add the emoji to your Markdown file (instead of copy/paste).

1. Confirm the emoji renders correctly on the Learn site when you preview your file during the pull-request process. Also, use a screen reader tool to confirm it reads the emoji correctly.

## Additional resources

- [Shared Image Gallery](https://review.learn.microsoft.com/content-production-service/internal/image-gallery?branch=main)
