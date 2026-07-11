---
title: SlidesAIAgent
second_title: Aspose.Slides for Java API 参考
description: 提供用于处理演示文稿的 AI 驱动功能。
type: docs
url: /zh/com.aspose.slides/slidesaiagent/
---
**继承：**
java.lang.Object
```
public class SlidesAIAgent
```

提供用于处理演示文稿的 AI 驱动功能。

## 构造函数

| Constructor | Description |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | 使用自定义 AI 客户端初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新实例。 |
| [SlidesAIAgent()](#SlidesAIAgent--) | 使用内置的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)（默认配置）初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新实例。 |

## 方法

| Method | Description |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | 使用 AI（同步版本）将演示文稿翻译为指定语言。 |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | 根据文本描述生成演示文稿实例。 |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | 根据文本描述生成演示文稿实例。 |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

使用自定义 AI 客户端初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新实例。使用此重载可以指定 AI 提供商、提供您自己的 LLM，或自定义连接（例如，提供您自己的 java.net.HttpURLConnection）。可以使用任何 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的实现。要使用内置的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)（默认配置），请改用 SlidesAIAgent() 重载。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI 客户端实例。可以使用任何 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 的实现。 |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

使用内置的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)（默认配置）初始化 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) 的新实例。该客户端连接到 Aspose 自有的 LLM，无需额外配置。若要使用其他 AI 客户端，请改用 SlidesAIAgent(IAIWebClient) 重载。

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

使用 AI（同步版本）将演示文稿翻译为指定语言。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目标演示文稿 |
| language | java.lang.String | 目标语言 |

--------------------

下面的示例使用默认的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)，该实例由无参 SlidesAIAgent() 构造函数创建，并连接到 Aspose 自有的 LLM。若要使用其他 AI 提供商、提供您自己的 LLM，或自定义连接（例如，提供您自己的 java.net.HttpURLConnection），请向 SlidesAIAgent(IAIWebClient) 构造函数传入 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 实现。

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

根据文本描述生成演示文稿实例。提供所需语言的主题、想法、引语或文本片段。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | 主题、想法、引语或文本片段。 |
| presentationContentAmount | int | 生成的演示文稿中的内容数量。 |

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

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

根据文本描述生成演示文稿实例。提供所需语言的主题、想法、引语或文本片段。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | 主题、想法、引语或文本片段。 |
| presentationContentAmount | int | 生成的演示文稿中的内容数量。 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | 用于布局和设计的演示文稿模板，替代默认模板。 |

--------------------

下面的示例使用默认的 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)，该实例由无参 SlidesAIAgent() 构造函数创建，并连接到 Aspose 自有的 LLM。若要使用其他 AI 提供商、提供您自己的 LLM，或自定义连接（例如，提供您自己的 java.net.HttpURLConnection），请向 SlidesAIAgent(IAIWebClient) 构造函数传入 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 实现。

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

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation)