---
title: OpenAIWebClient
second_title: Aspose.Slides for Android via Java API 参考
description: 内置轻量级 OpenAI Web 客户端
type: docs
url: /zh/com.aspose.slides/openaiwebclient/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

内置轻量级 OpenAI Web 客户端
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | 创建 OpenAI Web 客户端的实例。 |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 创建 OpenAI Web 客户端的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 使用外部管理的实例向 AI 模型发送聊天指令，并返回给定指令的响应消息。 |
| [createConversation()](#createConversation--) | 创建会话实例。 |
| [close()](#close--) | 释放此实例使用的资源。 |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

创建 OpenAI Web 客户端的实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 语言模型。可能的取值：- gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 密钥 |
| organizationId | java.lang.String | 组织 ID（可选） |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

创建 OpenAI Web 客户端的实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 语言模型。可能的取值：- gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 密钥 |
| organizationId | java.lang.String | 组织 ID（可选） |
| httpClient | java.net.HttpURLConnection | 外部管理的 HttpURLConnection 实例。 |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

使用外部管理的实例向 AI 模型发送聊天指令，并返回给定指令的响应消息。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型处理的指令或消息 |

**返回:**
java.lang.String - 对给定指令的响应中 AI 模型生成的消息。
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

创建会话实例。与常规 AI 调用不同，会话会保留完整的上下文。

**返回:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一个 [IAIConversation](../../com.aspose.slides/iaiconversation) 实例。
### close() {#close--}
```
public final void close()
```

释放此实例使用的资源。