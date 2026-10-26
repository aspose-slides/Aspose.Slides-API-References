---
title: SlidesAIAgent
second_title: Aspose.Slides for Java API 參考
description: 提供 AI 驅動的功能，用於處理簡報。
type: docs
url: /zh-hant/com.aspose.slides/slidesaiagent/
---
**繼承:**
java.lang.Object
```
public class SlidesAIAgent
```

提供 AI 驅動的功能，用於處理簡報。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initializes a new instance of [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) with a custom AI client. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initializes a new instance of [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) using the built-in [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) with its default configuration. |
## 方法

| 方法 | 說明 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Translates a presentation to the specified language using AI (synchronous version). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generates a presentation instance from a text description. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generates a presentation instance from a text description. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


使用自訂 AI 客戶端初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新實例。使用此多載可指定 AI 提供者、供應您自己的 LLM，或自訂連線（例如，提供您自己的 java.net.HttpURLConnection）。任何 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的實作皆可使用。若要使用內建的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) 並使用其預設設定，請改用  SlidesAIAgent()  多載。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI 客戶端實例。任何 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的實作皆可使用。 |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```


使用內建的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) 並使用其預設設定初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新實例。客戶端連接至 Aspose 的自有 LLM，且不需要額外設定。若要使用不同的 AI 客戶端，請改用 SlidesAIAgent(IAIWebClient) 多載。

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```


使用 AI（同步版本）將簡報翻譯為指定語言。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目標簡報 |
| language | java.lang.String | 目標語言

--------------------

以下範例使用預設的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)，該實例由無參數的 SlidesAIAgent() 建構式建立，並連接至 Aspose 的自有 LLM。若要使用不同的 AI 提供者、供應您自己的 LLM，或自訂連線（例如，提供您自己的 java.net.HttpURLConnection），請將 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 實作傳遞給 SlidesAIAgent(IAIWebClient) 建構式。

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```


從文字描述產生簡報實例。提供主題、想法、引文或文字片段，語言需符合需求。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| description | java.lang.String | 主題、想法、引文或文字片段。 |
| presentationContentAmount | int | 產生簡報的內容量。 |

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**傳回值:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


從文字描述產生簡報實例。提供主題、想法、引文或文字片段，語言需符合需求。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| description | java.lang.String | 主題、想法、引文或文字片段。 |
| presentationContentAmount | int | 產生簡報的內容量。 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | 用於版面與設計的簡報範本，取代預設範本。 

--------------------

以下範例使用預設的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)，該實例由無參數的 SlidesAIAgent() 建構式建立，並連接至 Aspose 的自有 LLM。若要使用不同的 AI 提供者、供應您自己的 LLM，或自訂連線（例如，提供您自己的 java.net.HttpURLConnection），請將 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 實作傳遞給 SlidesAIAgent(IAIWebClient) 建構式。

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**傳回值:**
[IPresentation](../../com.aspose.slides/ipresentation)