# 隱私說明

HourZero Desktop Pet Project Demo（以下叫「這個程式」）是 HourZero 個人開發的測試版。
我們盡量少收資料：大部分東西只存在你自己的電腦裡。

最後更新：2026-11-06

## 不會送給我們的
- 你丟進來的圖片、檔名、做好的桌寵。
- 你跟桌寵的對話、人設。
- 你填的 AI 服務金鑰（API key）。它存在 Windows 的「認證管理員」裡，只在你的電腦上。

這些都存在你自己的電腦裡（%LOCALAPPDATA% 底下這個程式的資料夾）。
你如果接了雲端 AI 服務，對話會從你的電腦**直接**送到你選的那家服務，不經過我們；那部分照那家服務的隱私政策。
用本機模型（例如 Ollama）時，對話不會離開你的電腦。

## 你按「送出回饋」時才會送的
- 你寫的那段文字和選的標籤。
- 信箱（**選填**，不填也能送；填了我們才能回你）。
- 你勾選的系統資訊：程式版本、Windows 版本、螢幕數量和縮放比例、丟過的圖片類型（只有像「PNG」「GIF」這樣的類型，不是圖片也不是檔名）。
- 你勾選「附上日誌」時的程式紀錄；送出前會把裡面你的 Windows 使用者名稱遮掉。

送出前會列出每一項，你可以取消勾選。

**送到哪**：先送到我們在 Cloudflare（美國）的轉送站，再轉進開發者的 Discord（美國）私人頻道。轉送站不留你的 IP；Cloudflare 和 Discord 照它們自己的隱私政策處理連線資料。

**拿來做什麼**：
- 回覆你的回饋。
- 改善這個程式和之後的正式版。
- 之後聯絡你：問你回饋的細節、請你試試修好的版本或新功能。
- 新版本通知：只有你另外勾了「之後有新版本可以寄信通知我」（選填，預設不勾）才會寄。每封通知信都會寫怎麼取消，回信說一聲就停。

我們不賣你的資料，也不拿去做這些用途以外的事。

**留多久**：每一則回饋（包括你填的信箱）會一直存在那個 Discord 頻道裡，**保存到你要求刪除為止**；這個專案停止時，整個頻道一起刪掉。
頻道是私人的，只有開發者看得到。

**怎麼要求刪除**：寫信到 contact@zerohour0x00.com，寫上你送回饋時填的信箱（沒填信箱的話，寫大概的時間和內容）。我們收到後會把那幾則回饋刪掉，並回信告訴你刪好了。只想取消新版本通知、不刪回饋也可以，信裡說一聲就好。

## 使用統計（預設關）
第一次打開時會問你要不要分享匿名使用統計，**預設是關的**，之後也能在系統匣選單（工作列右下角的圖示按右鍵）的「分享匿名使用統計」改。
打開的話只送匯總數字，例如某個按鈕被點了幾次、用了大約幾天（例如「4～7 天」）。
不送安裝編號、圖片、檔名、對話或任何能認出你的東西。

## 檢查更新
這個程式大約一天檢查一次 GitHub 上有沒有新版本。這時 GitHub 會看到你的 IP，照 GitHub 的隱私政策處理；我們拿不到。
可以在系統匣選單的「自動檢查更新」關掉自動檢查。

## 你的權利
你可以來信要求查詢、更正、刪除你送給我們的資料，或要我們停止使用。寄到 contact@zerohour0x00.com，寫上你送回饋時填的信箱或大概的時間和內容，我們會盡快處理。
存在你電腦裡的資料，刪掉這個程式的資料夾就沒了。

## 小朋友
未滿 13 歲請不要在回饋裡填信箱。

## 聯絡我們
HourZero：contact@zerohour0x00.com

這份說明改版時會更新上面的日期；有重大改變時會在程式裡或下載頁通知。

---

# Privacy Notice

HourZero Desktop Pet Project Demo ("the app") is a test build made by HourZero, an independent developer.
We collect as little as we can: most things stay on your own computer.

Last updated: 2026-11-06

## What we never receive
- Images you drop in, their file names, or the pets you make.
- Your chats with your pet and its persona.
- Your AI service API key. It is stored in Windows Credential Manager on your computer only.

All of this stays in the app's folder under %LOCALAPPDATA% on your computer.
If you connect a cloud AI service, your chats go **directly** from your computer to that service, not through us, and that service's privacy policy applies.
With a local model (such as Ollama), your chats never leave your computer.

## What is sent only when you press "Send feedback"
- The text you write and the tags you pick.
- Your email address (**optional**; we can only reply if you add it).
- The system info you leave checked: app version, Windows version, number of screens and scaling, and the types of images you've used (such as "PNG" or "GIF" — never the image or its file name).
- If you check "Attach log", the app log, with your Windows user name masked before sending.

Every item is listed before sending, and you can uncheck any of them.

**Where it goes**: to our relay on Cloudflare (US), which forwards it to a private channel on the developer's Discord (US). The relay does not store your IP address; Cloudflare and Discord handle connection data under their own privacy policies.

**What we use it for**:
- Replying to your feedback.
- Improving the app and the future full release.
- Contacting you later: asking about your feedback, or inviting you to try a fixed build or new feature.
- New-version notices: only if you also check "Email me when there's a new version" (optional, unchecked by default). Every notice tells you how to stop them; just reply and we'll stop.

We never sell your data or use it for anything beyond these purposes.

**How long we keep it**: each piece of feedback (including your email address) stays in that Discord channel **until you ask us to delete it**. If this project ends, we delete the whole channel.
The channel is private and only the developer can see it.

**How to ask for deletion**: email contact@zerohour0x00.com with the email address you used in your feedback (or, if you didn't add one, roughly when you sent it and what it said). We'll delete that feedback and email you back once it's done. If you only want to stop new-version notices and keep your feedback, just say so.

## Usage statistics (off by default)
On first launch the app asks whether you want to share anonymous usage statistics. **It is off by default**, and you can change it at any time from the system tray menu (right-click the app's icon at the bottom right of the taskbar).
If you turn it on, the app only sends totals, such as how many times a button was clicked or roughly how many days you've used the app (for example "4–7 days").
It never sends an install ID, images, file names, chats, or anything that identifies you.

## Update checks
About once a day the app checks GitHub for a new version. GitHub can see your IP address and handles it under its own privacy policy; we never receive it.
You can turn off automatic checks from the system tray menu.

## Your rights
You can ask us to show, correct, or delete the data you sent us, or to stop using it. Email contact@zerohour0x00.com with the email address you used in your feedback, or roughly when you sent it and what it said.
Data stored on your computer is removed when you delete the app's folder.

## Children
If you are under 13, please don't include an email address in your feedback.

## Contact
HourZero: contact@zerohour0x00.com

When this notice changes, we update the date above; for major changes we'll let you know in the app or on the download page. If the Chinese and English versions differ, the Chinese version applies.
