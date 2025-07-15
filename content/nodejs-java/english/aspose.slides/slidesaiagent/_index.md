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
| aiClient | [OpenAIWebClient](../openaiwebclient) | AI client instance |

 **Returns:**
SlidesAIAgent

 **Error**

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | if AI client is not provided |


---


### generatePresentation {#generatePresentation}

| Name | Description |
| --- | --- |
| generatePresentation (String, int) | Generates a presentation from a text description |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| description | String | The topic, ideas, quotes or text snippets |
| presentationContentAmount | int | Amount of content in resulting presentation |

 **Returns:**
[Presentation](../presentation)

 **Error**

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | if description is empty |


---


### generatePresentation {#generatePresentation}

| Name | Description |
| --- | --- |
| generatePresentation (String, int, [Presentation](../presentation)) | Generates a presentation using custom template |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| description | String | The topic, ideas, quotes or text snippets |
| presentationContentAmount | int | Amount of content in resulting presentation |
| presentationTemplate | [Presentation](../presentation) | Presentation template for layout and design |

 **Returns:**
[Presentation](../presentation)

 **Error**

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | if parameters are invalid |


---


### translate {#translate}

| Name | Description |
| --- | --- |
| translate ([Presentation](../presentation), String) | Translates a presentation to the specified language using AI |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | Target presentation |
| language | String | Target language |

 **Error**

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | if parameters are invalid |


---


