---
title: OpenAIWebClient
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 內建輕量級 OpenAI 網路客戶端
type: docs
url: /zh-hant/com.aspose.slides/openaiwebclient/
---
**繼承：**
java.lang.Object

**所有已實作介面：**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

內建輕量級 OpenAI 網路客戶端
## 建構式

| 建構式 | 描述 |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | 建立 OpenAI Web 客戶端實例。 |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 建立 OpenAI Web 客戶端實例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 使用外部管理的實例向 AI 模型傳送聊天指令，並回傳對該指令的回應訊息。 |
| [createConversation()](#createConversation--) | 建立會話實例。 |
| [close()](#close--) | 釋放此實例使用的資源。 |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

建立 OpenAI Web 客戶端實例。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 語言模型。可能的值： - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 金鑰 |
| organizationId | java.lang.String | 組織 ID（可選） |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

建立 OpenAI Web 客戶端實例。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 語言模型。可能的值： - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 金鑰 |
| organizationId | java.lang.String | 組織 ID（可選） |
| httpClient | java.net.HttpURLConnection | 外部管理的 HttpURLConnection 實例。 |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

使用外部管理的實例向 AI 模型傳送聊天指令，並回傳對該指令的回應訊息。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型處理的指令或訊息 |

**傳回值：**
java.lang.String - AI 模型根據給定指令產生的訊息。

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

建立會話實例。與一般 AI 呼叫不同，會話會保留完整的上下文。

**傳回值：**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一個 [IAIConversation](../../com.aspose.slides/iaiconversation) 實例。

### close() {#close--}
```
public final void close()
```

釋放此實例使用的資源。