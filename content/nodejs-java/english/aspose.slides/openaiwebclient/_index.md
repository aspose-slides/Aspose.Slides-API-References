---
title: OpenAIWebClient
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/openaiwebclient/
---

## OpenAIWebClient class

 A built-in  IAIWebClient implementation that connects to the OpenAI API.
 
### OpenAIWebClient {#OpenAIWebClient}

| Name | Description |
| --- | --- |
| OpenAIWebClient(String, String, String) | Creates an instance of the OpenAI web client. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| model | String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API key. |
| organizationId | String | Organization ID (optional). using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null)) { SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); using (Presentation presentation = new Presentation("Presentation.pptx")) { await aiAgent.TranslateAsync(presentation, "spanish"); presentation.Save("translated.pptx", SaveFormat.Pptx); } } |

 **Returns:**
OpenAIWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Text model value can't be null or empty. |


---


### OpenAIWebClient {#OpenAIWebClient}

| Name | Description |
| --- | --- |
| OpenAIWebClient(String, String, String, HttpURLConnection) | Creates an instance of the OpenAI web client that uses an externally managed HttpClient. The provided HttpClient is not disposed by this instance and remains owned by the caller. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| model | String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API key |
| organizationId | String | Organization ID (optional) |
| httpClient | HttpURLConnection | An externally managed `HttpClient` instance using (HttpClient httpClient = new HttpClient()) { OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient); SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient); using (Presentation presentation = new Presentation("Presentation.pptx")) { await aiAgent.TranslateAsync(presentation, "spanish"); presentation.Save("translated.pptx", SaveFormat.Pptx); } } |

 **Returns:**
OpenAIWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | HttpClient can't be null |


---


### callChat {#callChat}

| Name | Description |
| --- | --- |
| callChat (String) |  |

 **Returns:**
String


---


### close {#close}

| Name | Description |
| --- | --- |
| close () | Releases resources used by this instance. |


---


### createConversation {#createConversation}

| Name | Description |
| --- | --- |
| createConversation () | Creates a conversation instance. Unlike regular AI calls, conversations retain the entire context. |

 **Returns:**
OpenAIConversation


---


