---
title: SlidesAIAgent
second_title: Aspose.Slides for Android 的 Java API 參考
description: 提供 AI 驅動的功能以處理簡報。
type: docs
url: /zh-hant/com.aspose.slides/slidesaiagent/
---
**繼承：**
java.lang.Object
```
public class SlidesAIAgent
```

提供 AI 驅動的功能以處理簡報。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent 建構函式 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | 使用 AI 將簡報翻譯成指定語言（同步版本）。 |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | 根據文字描述產生簡報實例。 |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | 根據文字描述產生簡報實例。 |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

SlidesAIAgent 建構函式

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI 客戶端實例 |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

使用 AI 將簡報翻譯成指定語言（同步版本）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目標簡報 |
| language | java.lang.String | 目標語言

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

根據文字描述產生簡報實例。提供所需語言的主題、想法、引用或文字片段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| description | java.lang.String | 主題、想法、引用或文字片段。 |
| presentationContentAmount | int | 產生簡報的內容數量。

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

根據文字描述產生簡報實例。提供所需語言的主題、想法、引用或文字片段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| description | java.lang.String | 主題、想法、引用或文字片段。 |
| presentationContentAmount | int | 產生簡報的內容數量。 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | 用作版面配置與設計範本的簡報，取代預設範本。

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

**傳回值：**
[IPresentation](../../com.aspose.slides/ipresentation)