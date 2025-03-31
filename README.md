# obsidian-file-manager-plus
这是一个obsidian插件，增强型文件管理器，提供双列布局和高级文件操作功能。基于个人需求开发，需要自取，如果觉得不错，请点击star支持一下，谢谢
This is an Obsidian plugin, an enhanced file manager that provides dual column layout and advanced file manipulation functionality. Developed based on personal needs, self pickup is required. If you find it satisfactory, please click on Star Support. Thank you

完整的插件文件：
- main.js
- manifest.json
- styles.css
  
## 双列管理
![image](https://github.com/user-attachments/assets/66bdd6ac-8ed7-4d90-8837-8bc05e8bcae2)
支持文件聚焦，自动聚焦到正在打开编辑的文档的位置
## 文件右键
![image](https://github.com/user-attachments/assets/59627b81-5a6f-4d19-8fab-98ff04ac2114)
图中标注的功能，依赖其他插件
![image](https://github.com/user-attachments/assets/cefabf9b-1dc7-464a-86fb-7be155280cc7)

## 其他
请自行愉快探索

## 常见问题
- 查看root文件，点击文件夹空白处
  
### 主要特性

#### 1. 基础布局

- 默认在 Obsidian 左侧栏打开
- 双列布局：左侧文件夹树，右侧文件列表
- 支持拖拽调整列宽

#### 2. 文件夹列（左侧）功能

- 一键展开/折叠所有文件夹
- 文件夹右键菜单
  - 新建文件夹
  - 新建 Markdown 文件
  - 新建特殊文件（支持已安装插件的文件类型，如 Kanban）
  - 重命名文件夹
  - 删除文件夹（需二次确认）
- 显示文件夹内 .md 文件数量统计
- 支持自定义文件夹图标
- 不显示 vault 根目录

#### 3. 文件列（右侧）功能

- 自定义排序：
  - 按创建时间（升序/降序）
  - 按修改时间（升序/降序）
  - 按文件名（升序/降序）
- 文件右键菜单
  - 新建文件
  - 新建特殊文件（支持已安装插件的文件类型）
  - 重命名文件
  - 删除文件（需二次确认）
- 支持按住 Shift 多选文件
- 支持将选中文件拖动到左侧文件夹进行移动
- 文件预览悬停功能

#### 4. 搜索功能

- 快速搜索文件
- 支持文件名和内容搜索
- 实时搜索结果显示

#### 5. 插件设置

- 启动时自动打开插件视图（默认关闭）
- 忽略文件夹设置（支持正则表达式，逗号分隔）
- 忽略文件类型设置（支持正则表达式，逗号分隔）
- 重载文件树按钮
- 自定义文件夹和文件图标

## 使用方法

1. 安装插件后，点击左侧边栏的文件管理器图标打开插件
2. 在左侧浏览文件夹结构，右侧查看当前选中文件夹中的文件
3. 使用顶部工具栏进行搜索、排序和展开/折叠操作
4. 右键点击文件或文件夹访问上下文菜单
5. 通过插件设置页面自定义插件行为

## 安装方法

### 从 Obsidian 社区插件安装

1. 在 Obsidian 中打开设置
2. 进入第三方插件，关闭安全模式
3. 点击浏览社区插件
4. 搜索"文件管理器"并安装
5. 启用插件

### 手动安装

1. 下载最新版本的发布包
2. 解压缩到您的 vault 的 `.obsidian/plugins/` 目录下
3. 重新启动 Obsidian

## 许可证
GPL3.0
