---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
type: docs
url: /zh/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

表示一个对话实例。与常规 AI 调用不同，对话会保留完整的上下文。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | 发送包含完整上下文的会话请求消息并返回响应。 |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

发送包含完整上下文的会话请求消息并返回响应。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | AI 模型要处理的指令或消息。 |

**返回值：**
java.lang.String - 在给定指令的对话上下文中，AI 模型生成的消息。