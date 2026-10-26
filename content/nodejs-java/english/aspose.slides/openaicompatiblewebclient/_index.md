---
title: OpenAICompatibleWebClient
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/openaicompatiblewebclient/
---

## OpenAICompatibleWebClient class

 A built-in  IAIWebClient implementation that connects to an OpenAI-compatible LLM provider
 at a specified base URL.
 
### OpenAICompatibleWebClient {#OpenAICompatibleWebClient}

| Name | Description |
| --- | --- |
| OpenAICompatibleWebClient(String, String, String) | Creates an instance of the OpenAI-compatible web client. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| model | String | Model name supported by the LLM provider. |
| apiKey | String | API key (token). |
| baseUrl | String | Base URL of the OpenAI-compatible LLM. OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); Presentation presentation = new Presentation("Presentation.pptx"); try { aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } } finally { if (aiClient != null) aiClient.dispose(); } |

 **Returns:**
OpenAICompatibleWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Base URL value can't be null or empty. |


---


### OpenAICompatibleWebClient {#OpenAICompatibleWebClient}

| Name | Description |
| --- | --- |
| OpenAICompatibleWebClient(String, String, String, HttpURLConnection) | Creates an instance of the OpenAI-compatible web client that uses an externally managed HttpURLConnection. The provided HttpURLConnection is not disposed by this instance and remains owned by the caller. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| model | String | Model name supported by the LLM provider. |
| apiKey | String | API key (token). |
| baseUrl | String | Base URL of the OpenAI-compatible LLM. |
| httpClient | HttpURLConnection | An externally managed {@code HttpURLConnection} instance. URL url = new URL(url); HttpURLConnection httpClient = (HttpURLConnection) url.openConnection(); try { OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient); SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); Presentation presentation = new Presentation("Presentation.pptx"); try { aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } } finally { if (httpClient != null) httpClient.disconnect(); } |

 **Returns:**
OpenAICompatibleWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | HttpClient can't be null. |


---


### callChat {#callChat}

| Name | Description |
| --- | --- |
| callChat (String) | Sends a chat instruction to the AI model using an externally managed `HttpURLConnection` instance and returns response message to the given instruction. |

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


