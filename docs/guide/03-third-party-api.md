# 03. 连接第三方中转 API

第三方中转 API 适合不想自备网络环境、不想处理海外支付、不想从零配置 API 的用户，帮助你更快跑通 Codex。

## 现有入口

| 用途 | 链接 |
| --- | --- |
| 国内站登录 | `https://api.yoyochatai.com` |
| 充值/订阅相关入口 | `https://9.plus/shop/yoyoapi` |
| yoyo-plugin 下载 | `https://github.com/sasakihuang/yoyo-plugin/releases/` |
| 完整文档 | `https://github.com/sasakihuang/codex` |

## 它解决什么问题

- 不想自己处理网络访问环境。
- 不想研究官方订阅和支付路径。
- 想直接配置 API 后开始使用。
- 想把 Codex、图像模型和日常工具放到一个可用方案里。

## 它不是什么

国内站和中转 API 属于第三方接入方案，不是 OpenAI 官方订阅。它的价值是快速可用、低门槛和更省配置时间。

## 安全配置原则

- API Key 只通过环境变量或工具配置页保存。
- 不要把 API Key 写进仓库。
- 不要把 API Key 发给 Codex 让它直接贴到代码里。
- 不要在截图、日志、README 中暴露 key。
- 如果要让 Codex 帮你排查，提供错误类型，不提供完整密钥。

## 完成标准

你完成这一章时，应该能回答：

- 我现在走的是官方订阅，还是第三方中转？
- 登录入口是哪一个？
- API 配置在哪里？
- 哪些信息不能发给 Codex？

---

## 下一步

继续阅读 [04. 桌面 App 界面总览](04-app-tour.md)。
