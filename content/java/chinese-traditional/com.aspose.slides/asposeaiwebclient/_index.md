---
title: AsposeAIWebClient
second_title: Aspose.Slides for Java API 參考
description: 一個內建的實作，可連接至 Aspose 自己的 LLM。
type: docs
url: /zh-hant/com.aspose.slides/asposeaiwebclient/
---
**繼承：**
java.lang.Object

**全部已實作介面：**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

一個內建的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 實作，可連接至 Aspose 自己的 LLM。這是參數為空的 SlidesAIAgent() 建構函式所使用的預設用戶端。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | 建立 Aspose AI web client 的實例，以連接預設 Aspose LLM 端點。 |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 建立 Aspose AI web client 的實例，以使用外部管理的 HttpURLConnection 連接預設 Aspose LLM 端點。 |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | 建立 Aspose AI web client 的實例，以連接自訂端點 URL。 |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 建立 Aspose AI web client 的實例，以使用外部管理的 HttpURLConnection 連接自訂端點 URL。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 將聊天指令傳送至 AI 模型，並回傳對給定指令的回應訊息。 |
| [createConversation()](#createConversation--) | 建立對話實例。 |
| [dispose()](#dispose--) | 釋放此實例所使用的資源。 |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

建立連接預設 Aspose LLM 端點的 Aspose AI web client 實例。此用戶端是參數為空的 SlidesAIAgent() 建構函式所使用的客戶端，只有在直接將此客戶端傳遞給 SlidesAIAgent(IAIWebClient) 建構函式時才需要顯式建立。

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

建立使用外部管理的 HttpURLConnection 連接預設 Aspose LLM 端點的 Aspose AI web client 實例。此實例不會釋放提供的 HttpURLConnection，且該連線仍由呼叫端負責管理。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 外部管理的 HttpURLConnection 實例。

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

建立連接自訂端點 URL 的 Aspose AI web client 實例。當您擁有由 Aspose.Slides 團隊提供的 URL 時，請使用此重載；否則，請使用以預設 URL 的 AsposeAIWebClient() 重載。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 由 Aspose.Slides 團隊提供的 Aspose LLM 端點 URL。

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

建立使用外部管理的 HttpURLConnection 連接自訂端點 URL 的 Aspose AI web client 實例。此實例不會釋放提供的 HttpURLConnection，且該連線仍由呼叫端負責管理。當您擁有由 Aspose.Slides 團隊提供的 URL 且想自行提供 HttpURLConnection 時，請使用此重載；如果只需要在預設 URL 下使用自行提供的 HttpURLConnection，請改用 AsposeAIWebClient(HttpURLConnection) 重載。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| url | java.lang.String | 由 Aspose.Slides 團隊提供的 Aspose LLM 端點 URL。 |
| httpClient | java.net.HttpURLConnection | 外部管理的 HttpURLConnection 實例。

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

將聊天指令傳送至 AI 模型，並回傳對給定指令的回應訊息。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型處理的指令或訊息。

**傳回值：**
java.lang.String - AI 模型對給定指令產生的訊息。

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

建立對話實例。與一般的 AI 呼叫不同，對話會保留全部上下文。

**傳回值：**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一個 [IAIConversation](../../com.aspose.slides/iaiconversation) 實例。

### dispose() {#dispose--}
```
public final void dispose()
```

釋放此實例使用的資源。