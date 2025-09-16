---
title: SlidesAIAgent
second_title: Aspose.Sildes for PHP via Java API Reference
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
| aiClient | [OpenAIWebClient](../openaiwebclient) | AI client instance |

 **Returns:**
SlidesAIAgent

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | AI client instance is not provided |


---


### generatePresentation {#generatePresentation}

| Name | Description |
| --- | --- |
| generatePresentation (String, int) | Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| description | String | The topic, ideas, quotes, or text snippets. |
| presentationContentAmount | int | The amount of content in the resulting presentation. String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } |

 **Returns:**
[Presentation](../presentation)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | AI chat instruction can't be null or empty. |


---


### generatePresentation {#generatePresentation}

| Name | Description |
| --- | --- |
| generatePresentation (String, int, [Presentation](../presentation)) | Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| description | String | The topic, ideas, quotes, or text snippets. |
| presentationContentAmount | int | The amount of content in the resulting presentation. |
| presentationTemplate | [Presentation](../presentation) | A presentation to use as a template for layout and design, replacing the default template. String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; IPresentation template = new Presentation("masterPresentation.pptx"); try { OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } } finally { if (template != null) template.dispose(); } |

 **Returns:**
[Presentation](../presentation)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | AI chat instruction can't be null or empty. |


---


### translate {#translate}

| Name | Description |
| --- | --- |
| translate ([Presentation](../presentation), String) | Translates a presentation to the specified language using AI (synchronous version). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | Target presentation |
| language | String | Target language Presentation presentation = new Presentation("Presentation.pptx"); try { IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null); SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Language value can't be null or empty |


---


