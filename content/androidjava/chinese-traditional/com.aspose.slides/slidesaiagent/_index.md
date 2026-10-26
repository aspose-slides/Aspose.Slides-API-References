---
title: SlidesAIAgent
second_title: 適用於 Android 的 Aspose.Slides 透過 Java API 參考
description: 提供用於處理簡報的 AI 功能。
type: docs
url: /zh-hant/com.aspose.slides/slidesaiagent/
---
**Inheritance:**
java.lang.Object
```
public class SlidesAIAgent
```

提供用於處理簡報的 AI 功能。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | 使用自訂 AI 客戶端初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新執行個體。 |
| [SlidesAIAgent()](#SlidesAIAgent--) | 使用內建的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)（預設設定）初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | 使用 AI（同步版本）將簡報翻譯成指定語言。 |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | 根據文字說明產生簡報實例。 |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | 根據文字說明產生簡報實例。 |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

使用自訂 AI 客戶端初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新執行個體。使用此重載可指定 AI 供應者、提供您自己的 LLM，或自訂連線（例如，提供您自己的 java.net.HttpURLConnection）。任何 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的實作皆可使用。若要使用內建的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)（預設設定），請改用 SlidesAIAgent() 重載。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI 客戶端實例。任何 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的實作皆可使用。 |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

使用內建的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)（預設設定）初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新執行個體。此客戶端連線至 Aspose 自家的 LLM，無需額外設定。若要使用其他 AI 客戶端，請改用 SlidesAIAgent(IAIWebClient) 重載。

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

使用 AI（同步版本）將簡報翻譯成指定語言。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目標簡報 |
| language | java.lang.String | 目標語言 |

--------------------

以下範例使用預設的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)，其由無參數的 SlidesAIAgent() 建構函式建立，並連線至 Aspose 自家的 LLM。若要使用其他 AI 供應者、提供您自己的 LLM，或自訂連線（例如，提供您自己的 java.net.HttpURLConnection），請將 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的實作傳入 SlidesAIAgent(IAIWebClient) 建構函式。

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

根據文字說明產生簡報實例。請提供所需語言的主題、想法、引述或文字片段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| description | java.lang.String | 主題、想法、引述或文字片段。 |
| presentationContentAmount | int | 產生的簡報內容數量。 |

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**傳回值：**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

根據文字說明產生簡報實例。請提供所需語言的主題、想法、引述或文字片段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| description | java.lang.String | 主題、想法、引述或文字片段。 |
| presentationContentAmount | int | 產生的簡報內容數量。 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | 用作版面配置與設計範本的簡報，會取代預設範本。 |

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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

--------------------

以下範例使用預設的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)，其由無參數的 SlidesAIAgent() 建構函式建立，並連線至 Aspose 自家的 LLM。若要使用其他 AI 供應者、提供您自己的 LLM，或自訂連線（例如，提供您自己的 java.net.HttpURLConnection），請將 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的實作傳入 SlidesAIAgent(IAIWebClient) 建構函式。

**傳回值：**
[IPresentation](../../com.aspose.slides/ipresentation)