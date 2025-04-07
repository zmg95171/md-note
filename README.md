# MD笔记 (Markdown Notes)

![MD笔记标志](images/icon128.png)

一个简单、优雅的Markdown笔记Chrome扩展，支持标签管理、图片粘贴、实时预览等功能。

## 功能特点

- 📝 Markdown编辑与实时预览
- 🏷️ 标签系统（添加、筛选、搜索）
- 🖼️ 图片粘贴与上传
- 🔍 全文搜索功能
- 💾 离线存储，数据安全
- 🌙 暗色主题，护眼设计
- 📱 响应式界面，适应不同设备

## 安装方法

### 方法一：Chrome网上应用店安装（待发布）
1. 访问[Chrome网上应用店](https://chrome.google.com/webstore)
2. 搜索"MD笔记"
3. 点击"添加到Chrome"

### 方法二：开发者模式安装
1. 下载此仓库（Code > Download ZIP）
2. 解压到本地文件夹
3. 打开Chrome浏览器，访问 `chrome://extensions/`
4. 开启右上角的"开发者模式"
5. 点击"加载已解压的扩展程序"
6. 选择解压后的文件夹

## 使用指南

### 创建笔记
1. 点击插件图标打开MD笔记
2. 点击"新建笔记"按钮
3. 在编辑区域使用Markdown语法编写笔记

### Markdown语法
支持标准Markdown语法，包括：
- # 标题（多级）
- **粗体** 和 *斜体*
- 列表（有序和无序）
- [链接](https://example.com)
- 表格
- 代码块

### 添加图片
1. 复制图片到剪贴板
2. 在编辑器中按Ctrl+V粘贴
3. 或点击"图片"按钮上传本地图片

### 标签管理
1. 在标签输入框中输入标签名称
2. 按Enter键或点击"添加标签"按钮
3. 在侧边栏的"标签筛选"区域可查看和筛选所有标签

### 搜索笔记
1. 在侧边栏上方的搜索框中输入关键词
2. 使用下拉菜单选择搜索范围（全部、标题、内容、标签）
3. 结果会实时显示在笔记列表中

## 开发指南

### 项目结构
```
md-notes/
├── background.js     # 后台服务脚本
├── popup.html        # 主界面HTML
├── script.js         # 主要功能脚本
├── styles.css        # 样式表
├── manifest.json     # 扩展配置文件
└── images/           # 图标和图片资源
```

### 技术栈
- 纯原生JavaScript，无依赖框架
- 使用marked.js处理Markdown渲染
- Chrome Storage API用于数据存储
- 支持localStorage作为备选存储方案

### 本地开发
1. 克隆仓库到本地
```
git clone https://github.com/yourusername/md-notes.git
```
2. 按照"开发者模式安装"的步骤加载扩展
3. 修改代码后，在扩展页面点击"重新加载"更新

## 贡献指南
欢迎提交Pull Request或Issue来改进这个项目！

1. Fork本仓库
2. 创建新分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开Pull Request

## 隐私政策
MD笔记尊重您的隐私：
- 所有数据存储在本地，不会上传到任何服务器
- 不收集任何个人信息
- 不包含任何跟踪或分析代码

## 许可证
本项目采用MIT许可证 - 详情请查看 [LICENSE](LICENSE) 文件

## 致谢
- [marked.js](https://marked.js.org/) - Markdown解析库
- 感谢所有贡献者和使用者的支持

---

2023 MD笔记团队 | 一个简单、优雅的Markdown笔记工具 
