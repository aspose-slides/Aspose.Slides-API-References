---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides voor Android via Java API-referentie
description: Een ingebouwde implementatie die verbinding maakt met een OpenAI-compatibele LLM-provider op een opgegeven basis-URL.
type: docs
url: /nl/com.aspose.slides/openaicompatiblewebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Een ingebouwde [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementatie die verbinding maakt met een OpenAI-compatibele LLM-provider op een opgegeven basis-URL.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Creates an instance of the OpenAI-compatible web client. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the OpenAI-compatible web client that uses an externally managed  HttpURLConnection . |

## Methods

| Methode | Beschrijving |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using an externally managed HttpURLConnection instance and returns response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Maakt een instantie van de OpenAI-compatibele webclient.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| model | java.lang.String | Modelnaam ondersteund door de LLM-provider. |
| apiKey | java.lang.String | API-sleutel (token). |
| baseUrl | java.lang.String | Basis-URL van de OpenAI-compatibele LLM. |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
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

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

Maakt een instantie van de OpenAI-compatibele webclient die een extern beheerde  HttpURLConnection  gebruikt. De meegeleverde  HttpURLConnection  wordt niet vrijgegeven door deze instantie en blijft eigendom van de aanroeper.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| model | java.lang.String | Modelnaam ondersteund door de LLM-provider. |
| apiKey | java.lang.String | API-sleutel (token). |
| baseUrl | java.lang.String | Basis-URL van de OpenAI-compatibele LLM. |
| httpClient | java.net.HttpURLConnection | Een extern beheerde  HttpURLConnection  instantie. |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

Verzendt een chat-instructie naar het AI-model met behulp van een extern beheerde HttpURLConnection-instantie en retourneert het antwoordbericht op de opgegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String | De instructie of het bericht dat door het AI-model moet worden verwerkt. |

**Retour:**
java.lang.String - Het bericht dat door het AI-model is gegenereerd als reactie op de opgegeven instructie.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Maakt een conversatie-instantie. In tegenstelling tot reguliere AI-oproepen behouden conversaties de volledige context.

**Retour:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Een [IAIConversation](../../com.aspose.slides/iaiconversation) instantie.

### dispose() {#dispose--}
```
public final void dispose()
```

Vrijgeeft de door deze instantie gebruikte middelen.