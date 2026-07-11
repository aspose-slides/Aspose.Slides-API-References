---
title: OpenAIWebClient
second_title: Aspose.Slides for Java API 參考
description: 內建的實作，可連接至 OpenAI API。
type: docs
url: /zh-hant/com.aspose.slides/openaiwebclient/
---
**繼承關係:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IIAWebClient, Closeable
```

一個內建的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 實作，可連接至 OpenAI API。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | 建立 OpenAI 網頁客戶端的實例。 |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 建立使用外部管理的 HttpClient 的 OpenAI 網頁客戶端實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 建立對話實例。 |
| [close()](#close--) | 釋放此實例使用的資源。 |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

建立 OpenAI 網頁客戶端的實例。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 語言模型。可能的值：- gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 金鑰。 |
| organizationId | java.lang.String | 組織 ID（可選）。 |
```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

建立使用外部管理的 HttpClient 的 OpenAI 網頁客戶端實例。提供的 HttpClient 不會由此實例釋放，仍由呼叫端擁有。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 語言模型。可能的值：- gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 金鑰 |
| organizationId | java.lang.String | 組織 ID（可選） |
| httpClient | java.net.HttpURLConnection | 外部管理的 HttpClient 實例 |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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

使用提供的 HttpConnection 實例向 AI 模型發送聊天指示，並將回應訊息返回給給定的指示。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| instruction | java.lang.String |  |
**回傳值:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

建立對話實例。與一般的 AI 呼叫不同，對話會保留完整的上下文。

**回傳值:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一個 [IAIConversation](../../com.aspose.slides/iaiconversation) 實例。
### close() {#close--}
```
public final void close()
```

釋放此實例使用的資源。