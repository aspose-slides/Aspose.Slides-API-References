---
title: AsposeAIWebClient
second_title: Aspose.Slides for Java API 參考
description: 內建的實作，連接至 Aspose 自家的 LLM。
type: docs
url: /zh-hant/com.aspose.slides/asposeaiwebclient/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

一個內建的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 實作，連接至 Aspose 自己的 LLM。這是參數為空的 SlidesAIAgent() 建構函式所使用的預設客戶端。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | 建立一個連接至預設 Aspose LLM 端點的 Aspose AI 網路客戶端實例。 |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 建立一個使用外部管理的 HttpClient，連接至預設 Aspose LLM 端點的 Aspose AI 網路客戶端實例。 |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | 建立一個連接至自訂端點 URL 的 Aspose AI 網路客戶端實例。 |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 建立一個使用外部管理的 HttpClient，連接至自訂端點 URL 的 Aspose AI 網路客戶端實例。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 建立對話實例。 |
| [dispose()](#dispose--) | 釋放此實例使用的資源。 |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

建立一個連接至預設 Aspose LLM 端點的 Aspose AI 網路客戶端實例。這是參數為空的 SlidesAIAgent() 建構函式所使用的客戶端，因此僅在需要將客戶端直接傳遞給 SlidesAIAgent(IAIWebClient) 建構函式時才需要明確建立它。

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

建立一個使用外部管理的 HttpClient，連接至預設 Aspose LLM 端點的 Aspose AI 網路客戶端實例。提供的 HttpClient 不會由此實例釋放，仍由呼叫端負責管理。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 由外部管理的 HttpClient 實例。

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

建立一個連接至自訂端點 URL 的 Aspose AI 網路客戶端實例。當您取得 Aspose.Slides 團隊提供的 URL 時使用此載入項；否則，請使用預設 URL 的 AsposeAIWebClient() 載入項。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 由 Aspose.Slides 團隊提供的 Aspose LLM 端點 URL。

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

建立一個使用外部管理的 HttpClient，連接至自訂端點 URL 的 Aspose AI 網路客戶端實例。提供的 HttpClient 不會由此實例釋放，仍由呼叫端負責管理。當您取得 Aspose.Slides 團隊提供的 URL 且想自行提供 HttpClient 時使用此載入項；如果只需要自行提供 HttpClient 而使用預設 URL，請改用 AsposeAIWebClient(HttpClient) 載入項。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 由 Aspose.Slides 團隊提供的 Aspose LLM 端點 URL。 |
| httpClient | java.net.HttpURLConnection | 由外部管理的 HttpClient 實例。

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

使用提供的 HttpConnection 實例向 AI 模型傳送聊天指令，並返回對該指令的回應訊息。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| instruction | java.lang.String |  |

**傳回值：**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

建立對話實例。與一般 AI 呼叫不同，對話會保留完整的上下文。

**傳回值：**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一個 [IAIConversation](../../com.aspose.slides/iaiconversation) 實例。

### dispose() {#dispose--}
```
public final void dispose()
```

釋放此實例使用的資源。