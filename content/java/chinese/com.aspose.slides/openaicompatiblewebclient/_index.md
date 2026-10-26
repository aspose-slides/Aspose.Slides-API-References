---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Java API 参考
description: 一个内置实现，可在指定的基础 URL 上连接到兼容 OpenAI 的 LLM 提供程序。
type: docs
url: /zh/com.aspose.slides/openaicompatiblewebclient/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

一个内置的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 实现，可在指定的基础 URL 上连接到兼容 OpenAI 的 LLM 提供程序。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | 创建 OpenAI 兼容的 Web 客户端实例。 |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 创建一个使用外部管理的 HttpURLConnection 的 OpenAI 兼容的 Web 客户端实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 使用外部管理的 HttpURLConnection 实例向 AI 模型发送聊天指令，并返回给定指令的响应消息。 |
| [createConversation()](#createConversation--) | 创建一个会话实例。 |
| [dispose()](#dispose--) | 释放此实例使用的资源。 |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

创建 OpenAI 兼容的 Web 客户端实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| model | java.lang.String | LLM 提供程序支持的模型名称。 |
| apiKey | java.lang.String | API 密钥（令牌）。 |
| baseUrl | java.lang.String | 兼容 OpenAI 的 LLM 的基础 URL。 |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

创建一个使用外部管理的 HttpURLConnection 的 OpenAI 兼容的 Web 客户端实例。提供的 HttpURLConnection 不会由此实例释放，而仍归调用方所有。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| model | java.lang.String | LLM 提供程序支持的模型名称。 |
| apiKey | java.lang.String | API 密钥（令牌）。 |
| baseUrl | java.lang.String | 兼容 OpenAI 的 LLM 的基础 URL。 |
| httpClient | java.net.HttpURLConnection | 外部管理的 HttpURLConnection 实例。 |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

使用外部管理的 HttpURLConnection 实例向 AI 模型发送聊天指令，并返回给定指令的响应消息。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型处理的指令或消息。 |

**返回值:**
java.lang.String - 对给定指令作出响应的 AI 模型生成的消息。

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

创建一个会话实例。与普通的 AI 调用不同，会话会保留完整的上下文。

**返回值:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一个 [IAIConversation](../../com.aspose.slides/iaiconversation) 实例。

### dispose() {#dispose--}
```
public final void dispose()
```

释放此实例使用的资源。