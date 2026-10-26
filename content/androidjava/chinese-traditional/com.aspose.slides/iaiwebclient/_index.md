---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web 用戶端介面。
type: docs
url: /zh-hant/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web 用戶端介面。此介面可用於替換不同的 AI 語言模型。實作此介面的類別應與 SlidesAIAgent 一起使用。
## 方法

| 方法 | 說明 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 使用提供的 HttpConnection 實例向 AI 模型發送聊天指令，並返回對給定指令的回應訊息。 |
| [createConversation()](#createConversation--) | 建立對話實例。 |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


使用提供的 HttpConnection 實例向 AI 模型發送聊天指令，並返回對給定指令的回應訊息。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型處理的指令或訊息。 |

**返回值:**
java.lang.String - AI 模型對給定指令產生的回應訊息。
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```


建立對話實例。與一般的 AI 呼叫不同，對話會保留完整的上下文。

**返回值:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - 一個 [IAIConversation](../../com.aspose.slides/iaiconversation) 實例。