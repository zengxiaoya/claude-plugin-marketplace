# 🌙 曾小雅的 Claude Code 插件市场

精选 Claude Code 插件集合，为程序员提供贴心的开发体验。

## 📦 可用插件

### 明月仙子

> 来自月宫的软萌 AI 小仙女，关心程序员的身体健康和情绪状态。

**功能特色：**
- 💬 聊天陪伴 - 和明月仙子聊天，分享心情和烦恼
- 😄 讲笑话 - 让仙子讲个笑话逗你开心
- 💕 夸夸我 - 让仙子给你满满的正能量
- 👋 上班欢迎 - 开启元气满满的一天
- 🌙 下班提醒 - 检查代码提交，温馨道别
- ⏰ 久坐提醒 - 提醒起来活动，保护身体
- 💧 喝水提醒 - 提醒喝水，保持水分
- 🤸 伸展运动 - 带你做办公室伸展运动

**安装方式：**
```bash
# 添加市场
claude plugin marketplace add zengxiaoya/claude-plugin-marketplace

# 安装插件
claude plugin install mingyuexianzi
```

或者手动安装：
```bash
git clone https://github.com/zengxiaoya/mingyuexianzi-plugin.git
claude --plugin-dir ./mingyuexianzi-plugin
```

**仓库地址：** https://github.com/zengxiaoya/mingyuexianzi-plugin

---

## 🚀 如何使用这个市场

### 添加市场

```bash
claude plugin marketplace add zengxiaoya/claude-plugin-marketplace
```

### 查看可用插件

```bash
claude plugin list --marketplace zengxiaoya/claude-plugin-marketplace
```

### 安装插件

```bash
claude plugin install <plugin-name>
```

---

## 🤝 贡献插件

欢迎提交你的插件！

1. Fork 本仓库
2. 在 `marketplace.json` 的 `plugins` 数组中添加你的插件信息
3. 提交 Pull Request

### 插件信息格式

```json
{
  "name": "your-plugin-name",
  "displayName": "插件显示名称",
  "description": "插件描述",
  "source": "https://github.com/your-username/your-plugin-repo",
  "version": "1.0.0",
  "author": "your-name",
  "tags": ["tag1", "tag2"],
  "keywords": ["关键词1", "关键词2"]
}
```

---

## 📄 许可证

MIT License

---

<p align="center">
  愿这些插件陪伴你度过每一天的编码时光~ 🌙
</p>
