---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides 的 Java API 參考
description: 一個內建的實作，可於指定的基礎 URL 連接至相容 OpenAI 的 LLM 提供者。
type: docs
url: /zh-hant/com.aspose.slides/openaicompatiblewebclient/
---
**繼承：**
java.lang.Object

**全部已實作的介面：**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

一個內建的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 實作，能於指定的基礎 URL 連接至相容 OpenAI 的 LLM 提供者。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | 建立 OpenAI 相容的 Web 客戶端實例。 |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 建立使用外部管理的 HttpURLConnection 的 OpenAI 相容 Web 客戶端實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 使用外部管理的 HttpURLConnection 實例向 AI 模型發送聊天指令，並回傳對給定指令的回應訊息。 |
| [createConversation()](#createConversation--) | 建立會話實例。 |
| [dispose()](#dispose--) | 釋放此實例使用的資源。 |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

建立 OpenAI 相容的 Web 客戶端實例。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| model | java.lang.String | LLM 提供者支援的模型名稱。 |
| apiKey | java.lang.String | API 金鑰（令牌）。 |
| baseUrl | java.lang.String | OpenAI 相容 LLM 的基礎 URL。 |
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

建立使用外部管理的 HttpURLConnection 的 OpenAI 相容 Web 客戶端實例。提供的 HttpURLConnection 不會被此實例處置，且仍由呼叫端擁有。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| model | java.lang.String | LLM 提供者支援的模型名稱。 |
| apiKey | java.lang.String | API 金鑰（令牌）。 |
| baseUrl | java.lang.String | OpenAI 相容 LLM 的基礎 URL。 |
| httpClient | java.net.HttpURLConnection | 一個外部管理的 HttpURLConnection 實例。 |
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

使用外部管理的 HttpURLConnection 實例向 AI 模型發送聊天指令，並回傳對給定指令的回應訊息。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型處理的指令或訊息。 |

**傳回：**
java.lang.String - 針對給定指令由 AI 模型產生的訊息。

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

建立會話實例。與一般的 AI 呼叫不同，會話會保留完整的上下文。

**傳回：**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一個 [IAIConversation](../../com.aspose.slides/iaiconversation) 實例。

### dispose() {#dispose--}
```
public final void dispose()
```

釋放此實例使用的資源。