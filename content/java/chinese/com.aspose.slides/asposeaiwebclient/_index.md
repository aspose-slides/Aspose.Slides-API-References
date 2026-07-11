---
title: AsposeAIWebClient
second_title: Aspose.Slides Java API 参考
description: 一个内置的实现，连接到 Aspose 自己的 LLM。
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

一个内置的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 实现，连接到 Aspose 自己的 LLM。此客户端是无参数  SlidesAIAgent()  构造函数使用的默认客户端。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | 创建一个连接到默认 Aspose LLM 端点的 Aspose AI Web 客户端实例。 |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 创建一个使用外部管理的 HttpClient 连接到默认 Aspose LLM 端点的 Aspose AI Web 客户端实例。 |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | 创建一个连接到自定义端点 URL 的 Aspose AI Web 客户端实例。 |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 创建一个使用外部管理的 HttpClient 连接到自定义端点 URL 的 Aspose AI Web 客户端实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 创建一个会话实例。 |
| [dispose()](#dispose--) | 释放此实例使用的资源。 |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

创建一个连接到默认 Aspose LLM 端点的 Aspose AI Web 客户端实例。这是无参数  SlidesAIAgent()  构造函数使用的客户端，只有在直接将客户端传递给  SlidesAIAgent(IAIWebClient)  构造函数时才需要显式创建它。

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

创建一个使用外部管理的 HttpClient 连接到默认 Aspose LLM 端点的 Aspose AI Web 客户端实例。提供的 HttpClient 不会被此实例释放，仍归调用方所有。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 一个外部管理的 HttpClient 实例。 |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

创建一个连接到自定义端点 URL 的 Aspose AI Web 客户端实例。当您拥有 Aspose.Slides 团队提供的 URL 时使用此重载；否则，请使用带默认 URL 的 AsposeAIWebClient() 重载。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM 的端点 URL，由 Aspose.Slides 团队提供。 |
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

创建一个使用外部管理的 HttpClient 连接到自定义端点 URL 的 Aspose AI Web 客户端实例。提供的 HttpClient 不会被此实例释放，仍归调用方所有。当您拥有 Aspose.Slides 团队提供的 URL 并希望提供自己的 HttpClient 时使用此重载；如果只需要在默认 URL 上使用自己的 HttpClient，请改用 AsposeAIWebClient(HttpClient) 重载。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | Aspose LLM 的端点 URL，由 Aspose.Slides 团队提供。 |
| httpClient | java.net.HttpURLConnection | 一个外部管理的 HttpClient 实例。 |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

使用提供的 HttpConnection 实例向 AI 模型发送聊天指令，并返回该指令的响应消息。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String |  |

**返回:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

创建一个会话实例。不同于常规 AI 调用，会话会保留完整的上下文。

**返回:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一个 [IAIConversation](../../com.aspose.slides/iaiconversation) 实例。

### dispose() {#dispose--}
```
public final void dispose()
```

释放此实例使用的资源。