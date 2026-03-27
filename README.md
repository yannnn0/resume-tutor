# 简历优化导师

AI-Powered Resume Coaching Web Application

## 项目简介

一个对话式的简历优化指导工具，通过 AI 帮助求职者优化简历。采用五步流程，确保每一步都达到专业标准。

## 功能特性

-  **PDF 简历解析** - 支持上传 PDF 或粘贴文本
-  **对话式交互** - 类似 ChatGPT 的聊天体验
-  **进度追踪** - 右侧实时显示当前优化步骤
-  **五步优化流程**
  - Step 1: 第一印象与初步诊断
  - Step 2: 地毯式深度审计
  - Step 3: 战略性修改蓝图
  - Step 4: 修改后的简历范本
  - Step 5: 最终裁决与行动清单
-  **质量把关** - AI 自主判断是否进入下一步

## 技术栈

- 纯 HTML/CSS/JavaScript (单文件应用)
- 智谱 AI API (glm-4 模型)
- PDF.js (PDF 解析)
- localStorage (状态持久化)

## 使用方法

1. 克隆仓库：
   ```bash
   git clone https://github.com/yannnn0/resume-tutor.git
   ```

2. 进入目录：
   ```bash
   cd resume-tutor
   ```

3. 启动本地服务器（由于浏览器安全限制，需要 HTTP 服务）：
   ```bash
   python3 -m http.server 8080
   ```

4. 打开浏览器访问：
   ```
   http://localhost:8080
   ```

5. 上传简历或粘贴文本，开始优化之旅

## 配置说明

如需使用自己的智谱 AI API Key，请修改 `index.html` 中的：

```javascript
const API_KEY = 'your-api-key-here';
```

获取 API Key: https://open.bigmodel.cn/

## 部署

项目可部署到任何静态托管服务：

- GitHub Pages
- Vercel
- Netlify

直接上传 `index.html` 和 `how-it-works.html` 即可。

## 许可证

MIT License

---

Built by [yannnn0](https://github.com/yannnn0)
