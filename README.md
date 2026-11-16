# 通用题库速查

导入题库，粘贴题目文字或截图，即可查找匹配的答案和来源。

[打开网页版](https://west-slope.github.io/question-search-tool/)

- 支持一次导入或分批追加 XLSX、DOCX、Markdown、TXT、CSV、TSV 和 PDF。PDF 优先读取文字层，扫描页会尝试识别，题库需要标明答案。
- 用 Ctrl + V 粘贴截图，也可以拖入或选择 PNG、JPG、WebP 图片。识别文字可在输入框中修正。
- 查询以题干为主，选项用于区分题干相近的候选。
- 题库、PDF 和截图在当前浏览器内处理。截图和 PDF 功能从本站加载运行组件；下载 `index.html` 后，仍可离线导入其他格式并查询文字。

## 浏览器组件

- [Tesseract.js 6.0.1](https://github.com/naptha/tesseract.js/releases/tag/v6.0.1) 与 [Tesseract.js Core 6.0.0](https://github.com/naptha/tesseract.js-core) 使用 LSTM 模式。简体中文和英语模型来自 [Tessdata](https://github.com/naptha/tessdata) 的 `4.0.0_best_int`。
- PDF 文件由 [Mozilla PDF.js 6.5.438](https://github.com/mozilla/pdf.js) 读取。组件和许可证随站点文件一起分发。
