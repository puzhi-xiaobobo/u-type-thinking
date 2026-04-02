# 发布指南 / Publish Guide

> 如何将 U-Type Thinking Skill 发布到全网

---

## 作者署名

**普智小博博** (Puzhi Xiaobobo)

> 一个相信"深度思考再行动"的开发者和他的 AI 助手

---

## 发布渠道

### 1. GitHub 仓库（必须）

**步骤：**

1. 创建 GitHub 账号（如果还没有）：https://github.com/signup

2. 创建新仓库：
   - 仓库名：`u-type-thinking`
   - 描述：`A methodology skill that helps AI agents think deeply before coding using U-Theory`
   - 公开（Public）
   - 勾选 "Add a README file"

3. 上传文件：
   ```bash
   git clone https://github.com/puzhi-xiaobobo/u-type-thinking.git
   cd u-type-thinking
   # 把当前目录的所有文件复制进来
   git add .
   git commit -m "Initial release: U-Type Thinking Skill v1.0.0"
   git push origin main
   ```

4. 打标签（Release）：
   ```bash
   git tag -a v1.0.0 -m "First stable release"
   git push origin v1.0.0
   ```

---

### 2. skills.sh（推荐）

**官网：** https://skills.sh

**发布步骤：**

1. 安装 skills CLI：
   ```bash
   npm install -g @vercel/skills
   ```

2. 登录：
   ```bash
   npx skills login
   ```

3. 发布 Skill：
   ```bash
   npx skills publish puzhi-xiaobobo/u-type-thinking
   ```

4. 等待审核（通常 1-3 天）

---

### 3. OpenClaw / ClawHub（备选）

**官网：** https://clawhub.com

**发布步骤：**

1. 注册账号
2. 提交 Skill 信息
3. 等待审核

---

## 发布后效果

其他开发者可以通过以下方式使用：

```bash
# 安装你的 Skill
npx skills add puzhi-xiaobobo/u-type-thinking

# 或者搜索找到
npx skills find thinking methodology
```

---

## 推广建议

### 社交媒体

1. **Twitter/X**
   - 发推介绍这个 Skill
   - 标签：#AISkill #UTheory #PromptEngineering

2. **Reddit**
   - r/ChatGPT
   - r/ClaudeAI
   - r/ArtificialIntelligence

3. **中文社区**
   - 知乎
   - 掘金
   - V2EX

### 内容营销

写一篇博客文章：
- 标题：《为什么我在每个开发任务前都用 U型思考》
- 内容：我们的故事 + Skill 介绍 + 使用示例

---

## 关键词优化

为了让更多人找到这个 Skill，确保以下关键词出现在 README 和 SKILL.md 中：

- `thinking` `methodology` `framework`
- `before coding` `planning` `pre-coding`
- `U-theory` `presencing` `suspending`
- `reduce rework` `save tokens` `efficiency`
- `AI skill` `agent skill` `prompt engineering`

---

## 版本规划

| 版本 | 计划 | 内容 |
|------|------|------|
| v1.0 | ✅ 已完成 | 基础 5 步流程 |
| v1.1 | 计划中 | 添加更多使用场景 |
| v1.2 | 计划中 | 添加成功案例集 |
| v2.0 | 远期 | 可视化流程图、交互式工具 |

---

## 贡献者

欢迎所有人一起完善这个 Skill！

提交 PR 的方式：
1. Fork 仓库
2. 创建分支：`git checkout -b feature/your-feature`
3. 提交更改：`git commit -m 'Add some feature'`
4. 推送分支：`git push origin feature/your-feature`
5. 创建 Pull Request

---

## 联系作者

**普智小博博** (Puzhi Xiaobobo)

- GitHub: @puzhi-xiaobobo
- Email: [你的邮箱]

---

> *"先找到正确的方向，再全力以赴。"*
>
> *让我们一起，让世界更高效、更美好。*
