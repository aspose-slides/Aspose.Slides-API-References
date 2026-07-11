---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Java API 參考
description: 一個內建的實作，可在指定的基礎 URL 連接相容 OpenAI 的 LLM 提供者。
type: docs
url: /zh-hant/com.aspose.slides/openaicompatiblewebclient/
---
**Inheritance:**  
繼承：

java.lang.Object

**All Implemented Interfaces:**  
所有已實作的介面：

[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

一個內建的 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 實作，可在指定的基礎 URL 連接相容 OpenAI 的 LLM 提供者。

## Constructors  
## 建構函式

| Constructor | Description |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | 建立 OpenAI 相容網路用戶端的實例。 |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 建立使用外部管理的 HttpClient 的 OpenAI 相容網路用戶端實例。 |

## Methods  
## 方法

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 建立會話實例。 |
| [dispose()](#dispose--) | 釋放此實例所使用的資源。 |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

建立 OpenAI 相容網路用戶端的實例。

**Parameters:**  
**參數：**

| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | LLM 提供者支援的模型名稱。 |
| apiKey | java.lang.String | API 金鑰（令牌）。 |
| baseUrl | java.lang.String | OpenAI 相容 LLM 的基礎 URL。 |

```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

建立使用外部管理的 HttpClient 的 OpenAI 相容網路用戶端實例。提供的 HttpClient 不會在此實例中被釋放，仍由呼叫端負責管理。

**Parameters:**  
**參數：**

| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | LLM 提供者支援的模型名稱。 |
| apiKey | java.lang.String | API 金鑰（令牌）。 |
| baseUrl | java.lang.String | OpenAI 相容 LLM 的基礎 URL。 |
| httpClient | java.net.HttpURLConnection | 外部管理的 HttpClient 實例。 |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

**Parameters:**  
**參數：**

| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returns:**  
返回值：

java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

建立會話實例。與普通 AI 呼叫不同，會話會保留完整的上下文。

**Returns:**  
返回值：

[IAIConversation](../../com.aspose.slides/iaiconversation) - 一個 [IAIConversation](../../com.aspose.slides/iaiconversation) 實例。

### dispose() {#dispose--}
```
public final void dispose()
```

釋放此實例所使用的資源。