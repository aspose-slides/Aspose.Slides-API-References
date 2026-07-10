---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API 参考
description: AI Web 客户端接口。
type: docs
url: /zh/com.aspose.slides/iaiwebclient/
---
```
public interface IAIWebClient
```

AI Web 客户端接口。此接口允许替换不同的 AI 语言模型。实现此接口的类应与 SlidesAIAgent 一起使用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 使用提供的 HttpConnection 实例向 AI 模型发送聊天指令，并返回对给定指令的响应消息。 |
| [createConversation()](#createConversation--) | 创建会话实例。 |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

使用提供的 HttpConnection 实例向 AI 模型发送聊天指令，并返回对给定指令的响应消息。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型处理的指令或消息。 |

**返回值：**
java.lang.String - 对给定指令的响应中 AI 模型生成的消息。
### createConversation() {#createConversation--}
```
public abstract IIAConversation createConversation()
```

创建会话实例。与常规 AI 调用不同，会话会保留完整的上下文。

**返回值：**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一个 [IAIConversation](../../com.aspose.slides/iaiconversation) 实例。