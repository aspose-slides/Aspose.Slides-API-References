---
title: AsposeAIWebClient
second_title: Aspose.Slides for Java API 参考
description: 一个内置实现，连接到 Aspose 自己的 LLM。
type: docs
url: /zh/com.aspose.slides/asposeaiwebclient/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

一个内置的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 实现，连接到 Aspose 自己的 LLM。这是参数无参的  SlidesAIAgent()  构造函数使用的默认客户端。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | 创建一个 Aspose AI web client 实例，连接到默认的 Aspose LLM 端点。 |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 创建一个 Aspose AI web client 实例，连接到默认的 Aspose LLM 端点，使用外部管理的  HttpURLConnection 。 |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | 创建一个 Aspose AI web client 实例，连接到自定义端点 URL。 |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 创建一个 Aspose AI web client 实例，连接到自定义端点 URL，使用外部管理的  HttpURLConnection 。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 向 AI 模型发送聊天指令，并返回对给定指令的响应消息。 |
| [createConversation()](#createConversation--) | 创建一个会话实例。 |
| [dispose()](#dispose--) | 释放此实例使用的资源。 |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

创建一个 Aspose AI web client 实例，连接到默认的 Aspose LLM 端点。这是参数无参的  SlidesAIAgent()  构造函数使用的客户端，因此只有在将该客户端直接传递给  SlidesAIAgent(IAIWebClient)  构造函数时才需要显式创建它。

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
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
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

创建一个 Aspose AI web client 实例，使用外部管理的  HttpURLConnection  连接到默认的 Aspose LLM 端点。提供的  HttpURLConnection  不会被此实例释放，仍由调用方拥有。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 一个外部管理的  HttpURLConnection  实例。

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
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

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

创建一个 Aspose AI web client 实例，连接到自定义端点 URL。当您拥有由 Aspose.Slides 团队提供的 URL 时使用此重载；否则，请使用带有默认 URL 的  AsposeAIWebClient()  重载。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM 的端点 URL，由 Aspose.Slides 团队提供。

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
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

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

创建一个 Aspose AI web client 实例，使用外部管理的  HttpURLConnection  连接到自定义端点 URL。提供的  HttpURLConnection  不会被此实例释放，仍由调用方拥有。当您拥有由 Aspose.Slides 团队提供的 URL 并且想要提供自己的  HttpURLConnection 时使用此重载；如果仅需要使用默认 URL 并自行提供  HttpURLConnection ，请改用  AsposeAIWebClient(HttpURLConnection)  重载。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM 的端点 URL，由 Aspose.Slides 团队提供。 |
| httpClient | java.net.HttpURLConnection | 一个外部管理的  HttpURLConnection  实例。

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

向 AI 模型发送聊天指令，并返回对给定指令的响应消息。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型处理的指令或消息。 |

**返回值:**
java.lang.String - 返回给定指令的 AI 模型生成的消息。

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

创建一个会话实例。与常规 AI 调用不同，会话会保留完整的上下文。

**返回值:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一个 [IAIConversation](../../com.aspose.slides/iaiconversation) 实例。

### dispose() {#dispose--}
```
public final void dispose()
```

释放此实例使用的资源。