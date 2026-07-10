---
title: SlidesAIAgent
second_title: Aspose.Slides for Android via Java API 参考
description: 提供用于处理演示文稿的 AI 驱动功能。
type: docs
url: /zh/com.aspose.slides/slidesaiagent/
---
**继承：**
java.lang.Object
```
public class SlidesAIAgent
```

提供用于处理演示文稿的 AI 功能。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | 使用 AI 将演示文稿翻译为指定语言（同步版本）。 |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | 从文本描述生成演示文稿实例。 |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | 从文本描述生成演示文稿实例。 |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

SlidesAIAgent 构造函数

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI 客户端实例 |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

使用 AI 将演示文稿翻译为指定语言（同步版本）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目标演示文稿 |
| language | java.lang.String | 目标语言

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

从文本描述生成演示文稿实例。提供所需语言的主题、想法、引语或文本片段。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| description | java.lang.String | 主题、想法、引语或文本片段。 |
| presentationContentAmount | int | 生成的演示文稿中内容的数量。

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

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

从文本描述生成演示文稿实例。提供所需语言的主题、想法、引语或文本片段。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| description | java.lang.String | 主题、想法、引语或文本片段。 |
| presentationContentAmount | int | 生成的演示文稿中内容的数量。 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | 用于布局和设计的模板演示文稿，替代默认模板。

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

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)