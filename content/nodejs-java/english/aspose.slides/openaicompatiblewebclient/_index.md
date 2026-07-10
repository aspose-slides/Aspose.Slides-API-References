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
| baseUrl | String | Base URL of the OpenAI-compatible LLM. using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1")) { SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); using (Presentation presentation = new Presentation("Presentation.pptx")) { await aiAgent.TranslateAsync(presentation, "spanish"); presentation.Save("translated.pptx", SaveFormat.Pptx); } } |

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
| OpenAICompatibleWebClient(String, String, String, HttpURLConnection) | Creates an instance of the OpenAI-compatible web client that uses an externally managed HttpClient. The provided HttpClient is not disposed by this instance and remains owned by the caller. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| model | String | Model name supported by the LLM provider. |
| apiKey | String | API key (token). |
| baseUrl | String | Base URL of the OpenAI-compatible LLM. |
| httpClient | HttpURLConnection | An externally managed {@code HttpClient} instance. using (HttpClient httpClient = new HttpClient()) { OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient); SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); using (Presentation presentation = new Presentation("Presentation.pptx")) { await aiAgent.TranslateAsync(presentation, "spanish"); presentation.Save("translated.pptx", SaveFormat.Pptx); } } |

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
| callChat (String) |  |

 **Returns:**
String


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


