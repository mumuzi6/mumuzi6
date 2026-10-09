[English](README.md) | **简体中文**

# 你好，我是 mumuzi6

**Java · AI Agent 应用开发 · 开源贡献**

我是一名 Java 开发者，关注 AI Agent 应用开发与可靠的工具集成。
近期的开源贡献主要围绕 MCP 的异步执行、取消传播和错误处理。

## 技术栈

- **编程语言：** Java
- **AI 与 MCP：** LangChain4j、Quarkus MCP Server、Model Context Protocol
- **工程实践：** Maven、Git、异步编程、回归测试

## 开源贡献

### 已合并

- **[LangChain4j #6584](https://github.com/langchain4j/langchain4j/pull/6584)**
  — 修复异步 MCP 工具调用的取消传播，并补充取消行为与监听器行为的回归测试。

- **[Quarkus MCP Server #1069](https://github.com/quarkiverse/quarkus-mcp-server/pull/1069)**
  — 修复客户端返回错误后，服务端发起的请求仍处于等待状态的问题，并通过 Streamable HTTP 补充回归测试。

### 尚未合并

- **[LangChain4j #6618](https://github.com/langchain4j/langchain4j/pull/6618)**
  — 提交异步 MCP 工具调用的多轮交互重试支持，涵盖超时、取消处理及相关回归测试。
  PR 目前处于开放状态，尚未合并。

## 代表项目

### Sutan

目前维护于私有仓库的个人项目，项目详情暂未公开。
