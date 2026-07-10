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
| SlidesAIAgent([OpenAIWebClient](../openaiwebclient)) | Initializes a new instance of SlidesAIAgent with a custom AI client. Use this overload to specify the AI provider, supply your own LLM, or customize the connection (for example, by providing your own java.net.HttpURLConnection). Any implementation of IAIWebClient can be used. To use the built-in AsposeAIWebClient with its default configuration, use the SlidesAIAgent() overload instead. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| aiClient | [OpenAIWebClient](../openaiwebclient) | AI client instance. Any implementation of IAIWebClient can be used. |

 **Returns:**
SlidesAIAgent

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | AI client instance is not provided. |


---


### SlidesAIAgent {#SlidesAIAgent}

| Name | Description |
| --- | --- |
| SlidesAIAgent([OpenAICompatibleWebClient](../openaicompatiblewebclient)) | Initializes a new instance of SlidesAIAgent with a custom AI client. Use this overload to specify the AI provider, supply your own LLM, or customize the connection (for example, by providing your own java.net.HttpURLConnection). Any implementation of IAIWebClient can be used. To use the built-in AsposeAIWebClient with its default configuration, use the SlidesAIAgent() overload instead. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| aiClient | [OpenAICompatibleWebClient](../openaicompatiblewebclient) | AI client instance. Any implementation of IAIWebClient can be used. |

 **Returns:**
SlidesAIAgent

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | AI client instance is not provided. |


---


### SlidesAIAgent {#SlidesAIAgent}

| Name | Description |
| --- | --- |
| SlidesAIAgent([AsposeAIWebClient](../asposeaiwebclient)) | Initializes a new instance of SlidesAIAgent with a custom AI client. Use this overload to specify the AI provider, supply your own LLM, or customize the connection (for example, by providing your own java.net.HttpURLConnection). Any implementation of IAIWebClient can be used. To use the built-in AsposeAIWebClient with its default configuration, use the SlidesAIAgent() overload instead. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| aiClient | [AsposeAIWebClient](../asposeaiwebclient) | AI client instance. Any implementation of IAIWebClient can be used. |

 **Returns:**
SlidesAIAgent

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | AI client instance is not provided. |


---


### SlidesAIAgent {#SlidesAIAgent}

| Name | Description |
| --- | --- |
| SlidesAIAgent() | Initializes a new instance of SlidesAIAgent using the built-in AsposeAIWebClient with its default configuration. The client connects to Aspose's own LLM and requires no additional configuration. To use a different AI client, use the SlidesAIAgent(IAIWebClient) overload instead. |

 **Returns:**
SlidesAIAgent


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

 **Error**

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
| presentationTemplate | [Presentation](../presentation) | A presentation to use as a template for layout and design, replacing the default template. The example below uses the default AsposeAIWebClient, which is created by the parameterless SlidesAIAgent() constructor and connects to Aspose's own LLM. To use a different AI provider, supply your own LLM, or customize the connection (for example, by providing your own java.net.HttpURLConnection), pass an IAIWebClient implementation to the SlidesAIAgent(IAIWebClient) constructor. String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; IPresentation template = new Presentation("masterPresentation.pptx"); try { OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } } finally { if (template != null) template.dispose(); } |

 **Returns:**
[Presentation](../presentation)

 **Error**

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
| language | String | Target language The example below uses the default AsposeAIWebClient, which is created by the parameterless SlidesAIAgent() constructor and connects to Aspose's own LLM. To use a different AI provider, supply your own LLM, or customize the connection (for example, by providing your own java.net.HttpURLConnection), pass an IAIWebClient implementation to the SlidesAIAgent(IAIWebClient) constructor. Presentation presentation = new Presentation("Presentation.pptx"); try { IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null); SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Language value can't be null or empty |


---


