---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Java API Reference
description: A built-in  implementation that connects to an OpenAI-compatible LLM provider at a specified base URL.
type: docs
url: /com.aspose.slides/openaicompatiblewebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

A built-in [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementation that connects to an OpenAI-compatible LLM provider at a specified base URL.
## Constructors

| Constructor | Description |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Creates an instance of the OpenAI-compatible web client. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the OpenAI-compatible web client that uses an externally managed  HttpClient . |
## Methods

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```


Creates an instance of the OpenAI-compatible web client.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Model name supported by the LLM provider. |
| apiKey | java.lang.String | API key (token). |
| baseUrl | java.lang.String | Base URL of the OpenAI-compatible LLM.

```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```


Creates an instance of the OpenAI-compatible web client that uses an externally managed  HttpClient . The provided  HttpClient  is not disposed by this instance and remains owned by the caller.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Model name supported by the LLM provider. |
| apiKey | java.lang.String | API key (token). |
| baseUrl | java.lang.String | Base URL of the OpenAI-compatible LLM. |
| httpClient | java.net.HttpURLConnection | An externally managed  HttpClient  instance.

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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
### dispose() {#dispose--}
```
public final void dispose()
```


Releases resources used by this instance.

