# 拾页 Keepage 隐私政策

最后更新：2026 年 10 月

拾页（Keepage）是一个浏览器扩展，用来保存网页正文、高亮和批注。

## 你的收藏只在本地

你保存的网址、标题、正文快照、高亮、备注、标签、分组和阅读设置，全部只保存在你这台电脑的浏览器本地存储（IndexedDB 和 chrome.storage.local）里，**不会发送到任何地方**。不需要注册账号。

卸载扩展或清除浏览器数据会删除这些数据。你可以在「设置与备份」里随时下载一份 JSON 备份，备份文件也只保存在你自己选择的位置。

## 匿名使用统计（可关闭）

为了了解哪些功能有人在用、决定后续改进方向，拾页默认会发送匿名使用统计。发送的内容只有：

- 一个随机生成的设备标识（不与你的身份、账号或浏览器信息关联）和扩展版本号
- 功能使用事件：打开扩展、保存（来源是弹窗还是右键、是否读到正文）、打开阅读页、新建高亮（颜色）、写备注、搜索（结果数量）、开始批量导入（篇数）、提交反馈（类型）

**不发送**网址、网站名、标题、正文、高亮和备注的内容、搜索词，也不记录你浏览了哪些网页。

你可以在「设置与备份 → 隐私」里关闭「发送匿名使用统计」，关闭后立即停止发送。

## 意见反馈

你在「设置与备份 → 意见反馈」里主动提交的内容、选填的联系方式，以及扩展版本号，会发送给开发者，用来回复和改进产品。

## 数据发送到哪里

匿名使用统计和意见反馈通过 HTTPS 发送到开发者自己运营的服务器，不使用第三方统计或广告服务。扩展同时会从这台服务器读取功能开关（例如临时关闭某个功能、维护通知），这个请求不包含你的任何收藏内容。

## 扩展什么时候读取网页

- 只有在你点击工具栏图标、按快捷键或使用右键菜单「保存到拾页」时，才读取当前这一个标签页的内容，用来提取正文。
- 使用「批量导入」时，扩展会请求你授权访问那一个网站，然后在后台读取你勾选的页面。授权只针对该网站，可以随时在浏览器的扩展设置里撤销。

扩展不会在你浏览网页时常驻读取页面，也不会读取你没有选择保存的页面。

## 第三方

拾页不出售、不与任何第三方共享数据。阅读模式里显示的图片直接从原网站加载，这和你直接打开原网页时一样。

## 联系

如有问题，可以在扩展的「意见反馈」里留言，或在 GitHub 仓库提交 issue。

---

# Keepage Privacy Policy

Last updated: October 2026

**Your library stays on your computer.** Everything you save (URLs, titles, article snapshots, highlights, notes, tags, groups and reader settings) is stored only in your browser's local storage and is never sent anywhere. No account is needed. Uninstalling the extension or clearing browser data deletes it; you can download a JSON backup at any time.

**Anonymous usage statistics (optional).** By default Keepage sends anonymous usage statistics: a randomly generated device ID, the extension version, and feature-use events (opening the extension, saving a page and whether text was extracted, opening the reader, creating a highlight and its color, adding a note, searching and the number of results, starting a batch import and the number of pages, submitting feedback and its type). It never sends URLs, site names, titles, article text, highlight or note content, search terms, or your browsing history. You can turn this off at any time in Settings → Privacy.

**Feedback.** Feedback you choose to submit, an optional contact, and the extension version are sent to the developer.

Statistics and feedback are sent over HTTPS to a server run by the developer; no third-party analytics or ad services are used. The extension also reads feature switches (such as maintenance notices) from that server; these requests contain none of your saved content.

The extension reads a page only when you click its toolbar icon, press its shortcut, or choose "Save to Keepage" from the context menu. For batch import, it asks for permission to access that one site and then reads only the pages you selected. You can revoke that permission at any time in your browser's extension settings.

Keepage does not sell or share data with third parties. Images in the reader load directly from the original site, just as they would when you open the page.
