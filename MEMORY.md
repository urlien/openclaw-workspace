# MEMORY.md - 长期记忆

## 用户信息
- 用户名：uerling
- GitHub：https://github.com/urlien（用户名：urlien）
- 系统：Windows（C:\Users\uerling）
- 时区：GMT+8
- 技术背景：非技术背景，首次部署 OpenClaw

## 重要事件

### 2026-06-15 上半场：OpenClaw 本地部署
- 从零在 Windows 上安装 OpenClaw
- 使用 OpenRouter（支付宝充值 $10）+ 微信渠道
- 创建 GitHub 仓库同步 workspace：https://github.com/urlien/openclaw-workspace
- ⚠️ GitHub Token 曾在聊天中暴露，需删除重新生成

### 2026-06-15 下半场：工作区重置
- 用户将自定义仓库克隆到 workspace，覆盖了默认模板
- 自定义 SOUL.md 包含大量安全协议（CoT安全思维链等）
- 决定重置回默认：删除 md 文件 + memory 目录 + attestation 文件 → `openclaw setup`
- 清空了所有会话记录
- 卸载了开机自启动服务，后又重新安装（保留服务，按需启动）

## 关键配置
- OpenClaw 版本：2026.6.6 (8c802aa)
- 模型：OpenRouter (openrouter/auto) — ⚠️ 有不稳定问题，建议指定具体模型
- 渠道：微信
- 搜索：Parallel Search (Free)
- Node.js：v24.16.0
- Git：v2.54.0.windows.1

## 用户偏好
- 不想开机自启动 OpenClaw
- 习惯用快捷方式双击启动
- 非技术背景，需要简单明了的操作指引
