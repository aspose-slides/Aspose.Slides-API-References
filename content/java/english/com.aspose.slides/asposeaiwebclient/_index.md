---
title: AsposeAIWebClient
second_title: Aspose.Slides for Java API Reference
description: A built-in  implementation that connects to Asposes own LLM.
type: docs
url: /com.aspose.slides/asposeaiwebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

A built-in [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementation that connects to Aspose's own LLM. This is the default client used by the parameterless  SlidesAIAgent()  constructor.
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint using an externally managed  HttpClient . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL using an externally managed  HttpClient . |
## Methods

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```


Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint. This is the client used by the parameterless  SlidesAIAgent()  constructor, so creating it explicitly is only required when passing the client to the  SlidesAIAgent(IAIWebClient)  constructor directly.

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```


Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint using an externally managed  HttpClient . The provided  HttpClient  is not disposed by this instance and remains owned by the caller.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | An externally managed  HttpClient  instance.

```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```


Creates an instance of the Aspose AI web client that connects to a custom endpoint URL. Use this overload when you have a URL provided by the Aspose.Slides team; otherwise, use the  AsposeAIWebClient()  overload with the default URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team.

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```


Creates an instance of the Aspose AI web client that connects to a custom endpoint URL using an externally managed  HttpClient . The provided  HttpClient  is not disposed by this instance and remains owned by the caller. Use this overload when you have a URL provided by the Aspose.Slides team and want to supply your own  HttpClient ; if you only need your own  HttpClient  with the default URL, use the  AsposeAIWebClient(HttpClient)  overload instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team. |
| httpClient | java.net.HttpURLConnection | An externally managed  HttpClient  instance.

```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

