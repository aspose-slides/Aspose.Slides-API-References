---
title: OpenAIWebClient
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/openaiwebclient/
---

## OpenAIWebClient class

 Build-in lightweight OpenAI web client
 
### OpenAIWebClient {#OpenAIWebClient}

| Name | Description |
| --- | --- |
| OpenAIWebClient(String, String, String) | Creates instance of OpenAI Web client. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| model | String | OpenAI language model (gpt-4o, gpt-4o-mini, etc.) |
| apiKey | String | OpenAI API key |
| organizationId | String | Organization ID (optional) |

 **Returns:**
OpenAIWebClient

 **Error**

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | if API key or model are null/empty |


---


### OpenAIWebClient {#OpenAIWebClient}

| Name | Description |
| --- | --- |
| OpenAIWebClient(String, String, String, HttpURLConnection) |  |

 **Returns:**
OpenAIWebClient


---


### callChat {#callChat}

| Name | Description |
| --- | --- |
| callChat (String) | Sends a chat instruction to the AI model using an externally managed instance and returns response message to the given instruction. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| instruction | String | The instruction or message to be processed by the AI model |

 **Returns:**
String

 **Exception**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.OperationCanceledException | If the current thread was interrupted while waiting. |


---


### close {#close}

| Name | Description |
| --- | --- |
| close () |  |

 **Returns:**
void


---


