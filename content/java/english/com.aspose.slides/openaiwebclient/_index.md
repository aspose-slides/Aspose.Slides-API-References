---
title: OpenAIWebClient
second_title: Aspose.Slides for Java API Reference
description: A built-in  implementation that connects to the OpenAI API.
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

A built-in [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementation that connects to the OpenAI API.
## Constructors

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Creates an instance of the OpenAI web client. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the OpenAI web client that uses an externally managed  HttpClient . |
## Methods

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [close()](#close--) | Releases resources used by this instance. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Creates an instance of the OpenAI web client.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API key. |
| organizationId | java.lang.String | Organization ID (optional).

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


Creates an instance of the OpenAI web client that uses an externally managed  HttpClient . The provided  HttpClient  is not disposed by this instance and remains owned by the caller.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API key |
| organizationId | java.lang.String | Organization ID (optional) |
| httpClient | java.net.HttpURLConnection | An externally managed HttpClient instance

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Sends a chat instruction to the AI model using a provided HttpConnection instance and return response message to the given instruction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returns:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Creates a conversation instance. Unlike regular AI calls, conversations retain the entire context.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### close() {#close--}
```
public final void close()
```


Releases resources used by this instance.

