# 📝 每日清单 Daily Todo List

一个简洁优雅的每日清单应用，支持任务管理、历史记录查看和本地存储。

A simple and elegant daily todo list application with task management, history viewing, and local storage.

## ✨ 功能特性 Features

- 🎯 **智能界面切换** - 每天开始时显示"创建清单"按钮，有任务时自动切换到管理界面
- ✅ **任务管理** - 添加、完成、删除待办事项
- 📅 **历史记录** - 查看不同日期的任务清单
- 🔄 **自动排序** - 未完成任务优先显示
- 💾 **本地存储** - 数据保存在浏览器本地，无需注册
- 📱 **响应式设计** - 适配桌面和移动设备

## 🚀 快速开始 Quick Start

1. 克隆仓库：
```bash
git clone https://github.com/yeban-ai/daily-todo-list.git
cd daily-todo-list
```

2. 直接在浏览器中打开 `index.html` 文件即可使用

或者使用本地服务器：
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

然后访问 `http://localhost:8000`

## 📖 使用说明 Usage

### 创建清单
- 首次访问或当天无任务时，点击"创建清单"按钮开始

### 添加任务
- 在输入框中输入任务内容
- 点击"添加"按钮或按回车键

### 管理任务
- ✅ 点击复选框标记任务完成/未完成
- 🗑️ 悬停任务项显示删除按钮
- 📅 使用日期选择器查看历史任务

## 🏗️ 技术架构 Architecture

- **前端**: 纯 HTML + CSS + JavaScript
- **存储**: localStorage (浏览器本地存储)
- **样式**: 现代化 CSS，支持响应式设计
- **兼容性**: 支持现代浏览器

## 📁 项目结构 Project Structure

```
daily-todo-list/
├── index.html              # 主应用文件
├── todo_data.json          # 示例数据文件
├── 每日清单需求文档.md      # 详细需求文档
└── README.md               # 项目说明
```

## 🔄 版本历史 Version History

### V3.0 (当前版本)
- 🎨 重新设计用户界面和交互流程
- ➕ 新增"创建清单"功能
- 🔧 重构JavaScript代码，修复所有功能问题
- 📱 优化界面布局和视觉层次

### V2.1
- ➕ 新增删除功能
- 🎯 悬浮显示删除按钮
- ⚠️ 二次确认防误删

### V1.0
- ✅ 基础任务管理功能
- 📅 历史记录查看
- 💾 本地数据存储

## 🤝 贡献 Contributing

欢迎提交 Issue 和 Pull Request！

## 📄 许可证 License

MIT License

## 🔗 相关链接 Links

- [在线演示 Live Demo](https://yeban-ai.github.io/daily-todo-list/)
- [需求文档](./每日清单需求文档.md)
- [问题反馈](https://github.com/yeban-ai/daily-todo-list/issues)

---

💡 **提示**: 这是一个纯前端应用，所有数据存储在浏览器本地。如需数据同步功能，请关注后续版本更新。
