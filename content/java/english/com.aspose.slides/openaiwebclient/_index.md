---
title: OpenAIWebClient
second_title: Aspose.Slides for Java API Reference
description: Build-in lightweight OpenAI web client
type: docs
url: /com.aspose.slides/openaiwebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Build-in lightweight OpenAI web client
## Constructors

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Creates instance of OpenAI Web client. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) |  |
## Methods

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using an externally managed  instance and returns response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [close()](#close--) |  |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Creates instance of OpenAI Web client.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | OpenAI language model (gpt-4o, gpt-4o-mini, etc.) |
| apiKey | java.lang.String | OpenAI API key |
| organizationId | java.lang.String | Organization ID (optional) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String |  |
| apiKey | java.lang.String |  |
| organizationId | java.lang.String |  |
| httpClient | java.net.HttpURLConnection |  |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Sends a chat instruction to the AI model using an externally managed  instance and returns response message to the given instruction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | The instruction or message to be processed by the AI model |

**Returns:**
java.lang.String - The message generated by the AI model in response to the given instruction.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Creates a conversation instance. Unlike regular AI calls, conversations retain the entire context.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### close() {#close--}
```
public void close()
```




