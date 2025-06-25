---
title: SlidesAIAgent
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidesaiagent/
---

## SlidesAIAgent class

 Provides AI-powered features for processing presentations.
 
### SlidesAIAgent {#SlidesAIAgent}

| Name | Description |
| --- | --- |
| SlidesAIAgent([OpenAIWebClient](../openaiwebclient)) | SlidesAIAgent function |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| null | [OpenAIWebClient](../openaiwebclient) | aiClient |

 **Returns:**
SlidesAIAgent

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | AI client instance is not provided |


---


### translate {#translate}

| Name | Description |
| --- | --- |
| translate ([Presentation](../presentation), String) | Translates a presentation to the specified language using AI. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | Target presentation |
| language | String | Target language |

 **Error**

| Error | Condition |
| --- | --- |
 | OperationCanceledException | if translation fails Example usage: Presentation presentation = new Presentation("Presentation.pptx"); try { IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null); SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } |


---


