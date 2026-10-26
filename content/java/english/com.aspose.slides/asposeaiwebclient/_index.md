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
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint using an externally managed  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the Aspose AI web client that connects to a custom endpoint URL using an externally managed  HttpURLConnection . |
## Methods

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model and returns response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```


Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint. This is the client used by the parameterless  SlidesAIAgent()  constructor, so creating it explicitly is only required when passing the client to the  SlidesAIAgent(IAIWebClient)  constructor directly.

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```


Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint using an externally managed  HttpURLConnection . The provided  HttpURLConnection  is not disposed by this instance and remains owned by the caller.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | An externally managed  HttpURLConnection  instance.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
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
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```


Creates an instance of the Aspose AI web client that connects to a custom endpoint URL using an externally managed  HttpURLConnection . The provided  HttpURLConnection  is not disposed by this instance and remains owned by the caller. Use this overload when you have a URL provided by the Aspose.Slides team and want to supply your own  HttpURLConnection ; if you only need your own  HttpURLConnection  with the default URL, use the  AsposeAIWebClient(HttpURLConnection)  overload instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team. |
| httpClient | java.net.HttpURLConnection | An externally managed  HttpURLConnection  instance.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Sends a chat instruction to the AI model and returns response message to the given instruction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | The instruction or message to be processed by the AI model. |

**Returns:**
java.lang.String - The message generated by the AI model in response to the given instruction.
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

