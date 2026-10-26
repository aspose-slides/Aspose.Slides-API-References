---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: 表示一个会话实例。
type: docs
url: /zh/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

表示一个会话实例。与常规 AI 调用不同，会话会保留整个上下文。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | 发送会话请求消息，包括整个上下文并返回响应。 |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

发送包含整个上下文的会话请求消息并返回响应。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型处理的指令或消息。 |

**返回值：**
java.lang.String - 在会话上下文中对给定指令的响应，由 AI 模型生成的消息。