# 万太仪器 · 高精度实验室电子天平

[![GitHub](https://img.shields.io/badge/GitHub-nbwantai.github.io-blue?style=flat&logo=github)](https://nbwantai.github.io)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Languages](https://img.shields.io/badge/lang-5%20种语言-orange)](#)

## 📋 项目简介

万太仪器官方网站源码 - 一家专业生产高精度实验室电子天平的公司。网站采用响应式设计，支持**五种语言**（英语、中文、印度语、马来语、法语），展示公司产品、技术规格和应用领域。

### ✨ 主要功能

- 🌐 **多语言支持**：一键切换5种语言，满足国际客户需求
- 🧭 **横向导航菜单**：平滑滚动至各板块
- 📸 **预留图片位**：虚线框标注，方便展示真实产品图
- 📇 **公司名片**：完整展示联系方式（电话、邮箱、地址、网址）
- 📱 **响应式设计**：完美适配手机、平板和电脑
- 🎯 **交互提示**：按钮点击均有友好反馈

## 🛠️ 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式设计（Flexbox/Grid）
- **JavaScript** - 语言切换、交互效果
- **Font Awesome 6** - 图标库（MIT许可证）
- **Google Fonts (Inter)** - 字体（OFL许可证）

## 📁 文件结构

```
万太仪器官网/
├── index.html          # 主页面（所有代码整合）
├── README.md           # 项目说明文件
└── images/             # （预留）产品图片目录
    ├── hero-balance.jpg
    ├── lab-environment.jpg
    ├── sensor.jpg
    └── ...
```

## 🚀 快速开始

### 1. 克隆项目
```bash
git clone https://github.com/nbwantai/nbwantai.github.io.git
cd nbwantai.github.io
```

### 2. 本地运行
直接用浏览器打开 `index.html` 即可，无需安装依赖。

### 3. 自定义修改
- **替换图片**：将您的产品图片放入 `images/` 文件夹，并更新 `<div class="img-placeholder">` 为 `<img src="images/your-image.jpg">`
- **修改产品参数**：在技术规格区域更新量程、精度等数值
- **更新联系方式**：已在名片区域预留您的信息

## 🌍 多语言切换

网站内置五种语言翻译包，位于 `<script>` 标签内的 `i18nData` 对象。如需增加新语言，只需添加对应键值对。

```javascript
// 示例：添加日语
ja: {
    nav_home: 'ホーム',
    hero_title: '高精度実験室電子天びん',
    // ... 其他字段
}
```

## 📝 自定义配置

### 修改联系方式
在 `i18nData` 对象中更新各语言的 `bc_phone`、`bc_address` 等字段。

### 修改产品规格
在技术规格区域的 `<div class="spec-list">` 中修改数值。

### 修改颜色主题
主色调为深蓝色 `#1e3c72`，可在 CSS 中全局搜索替换。

## 📄 版权声明

本项目中：

- **原创代码**（HTML/CSS/JS）：可自由使用、修改
- **Font Awesome 图标**：遵循 [MIT 许可证](https://fontawesome.com/license)
- **Google Fonts (Inter)**：遵循 [OFL 许可证](https://scripts.sil.org/OFL)

```
Icons by Font Awesome (MIT) · Fonts by Google Fonts (OFL)
本站原创代码可自由使用 · 保留图片位内容仅供参考
```

## 📞 联系方式

- **公司名称**：万太仪器
- **总部地址**：中国 · 浙江 · 余姚
- **电话**：+86 135 8676 1600
- **邮箱**：nbwantai@hotmail.com
- **网址**：[nbwantai.github.io](https://nbwantai.github.io)

## 🤝 贡献指南

欢迎提交 Issue 或 Pull Request 改进项目：

1. Fork 本项目
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的修改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 📊 项目状态

![GitHub last commit](https://img.shields.io/github/last-commit/nbwantai/nbwantai.github.io)
![GitHub issues](https://img.shields.io/github/issues/nbwantai/nbwantai.github.io)

---

**万太仪器** - 精准测量，值得信赖 🧪⚖️
