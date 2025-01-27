# ai_chat
# AI Chat Application with DeepSeek API

这是一个基于 **Python** 和 **DeepSeek API** 的 AI 聊天应用程序，使用 `tkinter` 构建图形用户界面（GUI）。  
用户可以通过该应用与 AI 进行实时对话，支持流式传输回复、自动保存聊天记录、新建聊天等功能。

## 主要功能
- **实时聊天**：与 AI 进行流畅的对话，支持流式传输回复。
- **自动保存**：聊天记录会自动保存到本地文件，重启后可继续上次对话。
- **新建聊天**：一键重置对话历史，开始新的聊天会话。
- **简洁界面**：使用 `tkinter` 构建的简单易用的图形界面。

## 技术栈
- **Python**：核心编程语言。
- **tkinter**：用于构建图形用户界面。
- **DeepSeek API**：提供 AI 聊天功能。
- **JSON**：用于保存和加载聊天记录。

## 简介
最小可行模型，可作为临时框架使用。
下载后在使用支持python的IDE打开，使用前请填入api key。python适应版本：3.13.1 而其他版本适用性未知。
在self.message,可修改rule来改变ai角色，回答方式等。
若想使用完全程序，请在回答下再次插入一条完成的回复链来进行上下文结合。
若又有报错如“****** is not ......”等，原因是未安装相应的python模块包。可通过pip install ****** 解决。亦可以手动安装模块。
若出现“错误信息<如error400>”，“正在处理上一条信息”等错误，可通过点击左侧新建聊天解决。
具体错误信息解释可移步https://api-docs.deepseek.com/zh-cn/faq/ 查询。
若出现错误信息如error tyep 等报错信息，请自行查询Deepseek 官网查询。
