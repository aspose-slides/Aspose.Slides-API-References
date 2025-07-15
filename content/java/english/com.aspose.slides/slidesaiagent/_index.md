---
title: SlidesAIAgent
second_title: Aspose.Slides for Java API Reference
description: Provides AI-powered features for processing presentations.
type: docs
url: /com.aspose.slides/slidesaiagent/
---
**Inheritance:**
java.lang.Object
```
public class SlidesAIAgent
```

Provides AI-powered features for processing presentations.
## Constructors

| Constructor | Description |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent constructor |
## Methods

| Method | Description |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Translates a presentation to the specified language using AI |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Generates a presentation from a text description |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Generates a presentation using custom template |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


SlidesAIAgent constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI client instance |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Translates a presentation to the specified language using AI

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Target presentation |
| language | java.lang.String | Target language |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public IPresentation generatePresentation(String description, int presentationContentAmount)
```


Generates a presentation from a text description

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | The topic, ideas, quotes or text snippets |
| presentationContentAmount | int | Amount of content in resulting presentation |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Generated presentation
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Generates a presentation using custom template

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | The topic, ideas, quotes or text snippets |
| presentationContentAmount | int | Amount of content in resulting presentation |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation template for layout and design |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Generated presentation
