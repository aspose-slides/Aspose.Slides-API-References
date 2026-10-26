---
title: AsposeAIWebClient
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/asposeaiwebclient/
---

## AsposeAIWebClient class

 A built-in  IAIWebClient implementation that connects to Aspose's own LLM.
 This is the default client used by the parameterless  SlidesAIAgent() constructor.
 
### AsposeAIWebClient {#AsposeAIWebClient}

| Name | Description |
| --- | --- |
| AsposeAIWebClient() | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint. This is the client used by the parameterless SlidesAIAgent() function, so creating it explicitly is only required when passing the client to the SlidesAIAgent(IAIWebClient) function directly. AsposeAIWebClient aiClient = new AsposeAIWebClient(); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); Presentation presentation = new Presentation("Presentation.pptx"); try { aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } } finally { if (aiClient != null) aiClient.dispose(); } |

 **Returns:**
AsposeAIWebClient


---


### AsposeAIWebClient {#AsposeAIWebClient}

| Name | Description |
| --- | --- |
| AsposeAIWebClient(HttpURLConnection) | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint using an externally managed HttpURLConnection. The provided HttpURLConnection is not disposed by this instance and remains owned by the caller. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| httpClient | HttpURLConnection | An externally managed {@code HttpURLConnection} instance. URL url = new URL(url); HttpURLConnection httpClient = (HttpURLConnection) url.openConnection(); try { AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient); SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); Presentation presentation = new Presentation("Presentation.pptx"); try { aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } } finally { if (httpClient != null) httpClient.disconnect(); } |

 **Returns:**
AsposeAIWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | HttpClient instance is not provided. |


---


### AsposeAIWebClient {#AsposeAIWebClient}

| Name | Description |
| --- | --- |
| AsposeAIWebClient(String) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL. Use this overload when you have a URL provided by the Aspose.Slides team; otherwise, use the AsposeAIWebClient() overload with the default URL. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| url | String | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team. AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); Presentation presentation = new Presentation("Presentation.pptx"); try { aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } } finally { if (aiClient != null) aiClient.dispose(); } |

 **Returns:**
AsposeAIWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | URL can't be null or empty. |


---


### AsposeAIWebClient {#AsposeAIWebClient}

| Name | Description |
| --- | --- |
| AsposeAIWebClient(String, HttpURLConnection) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL using an externally managed HttpURLConnection. The provided HttpURLConnection is not disposed by this instance and remains owned by the caller. Use this overload when you have a URL provided by the Aspose.Slides team and want to supply your own HttpURLConnection; if you only need your own HttpURLConnection with the default URL, use the AsposeAIWebClient(HttpURLConnection) overload instead. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| url | String | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team. |
| httpClient | HttpURLConnection | An externally managed {@code HttpURLConnection} instance. URL url = new URL(url); HttpURLConnection httpClient = (HttpURLConnection) url.openConnection(); try { AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient); SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); Presentation presentation = new Presentation("Presentation.pptx"); try { aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } } finally { if (httpClient != null) httpClient.disconnect(); } |

 **Returns:**
AsposeAIWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | HttpClient instance is not provided. |


---


### callChat {#callChat}

| Name | Description |
| --- | --- |
| callChat (String) | Sends a chat instruction to the AI model and returns response message to the given instruction. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| instruction | String | The instruction or message to be processed by the AI model. |

 **Returns:**
String

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | AI chat instruction can't be null or empty |


---


### createConversation {#createConversation}

| Name | Description |
| --- | --- |
| createConversation () | Creates a conversation instance. Unlike regular AI calls, conversations retain the entire context. |

 **Returns:**
OpenAIConversation


---


### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose () | Releases resources used by this instance. |


---


