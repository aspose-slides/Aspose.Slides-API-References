---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides voor Java API-referentie
description: Een ingebouwde implementatie die verbinding maakt met een OpenAI-compatibele LLM-provider via een opgegeven basis-URL.
type: docs
url: /nl/com.aspose.slides/openaicompatiblewebclient/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Een ingebouwde [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementatie die verbinding maakt met een OpenAI-compatibele LLM-provider via een opgegeven basis-URL.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Maakt een instantie van de OpenAI-compatibele webclient. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Maakt een instantie van de OpenAI-compatibele webclient die een extern beheerde  HttpClient  gebruikt. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Maakt een gesprek-instantie. |
| [dispose()](#dispose--) | Libereert bronnen die door deze instantie worden gebruikt. |
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
| baseUrl | java.lang.String | Basis-URL van de OpenAI-compatibele LLM.

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


Maakt een instantie van de OpenAI-compatibele webclient die een extern beheerde  HttpClient  gebruikt. De meegegeven  HttpClient  wordt niet door deze instantie vrijgegeven en blijft eigendom van de aanroeper.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| model | java.lang.String | Modelnaam ondersteund door de LLM-provider. |
| apiKey | java.lang.String | API-sleutel (token). |
| baseUrl | java.lang.String | Basis-URL van de OpenAI-compatibele LLM. |
| httpClient | java.net.HttpURLConnection | Een extern beheerde  HttpClient -instantie.

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


Stuurt een chat-instructie naar het AI-model met behulp van een provided HttpConnection-instantie en retourneert het responsbericht voor de gegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returns:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Maakt een gesprek-instantie. In tegenstelling tot reguliere AI-aanroepen behouden gesprekken de volledige context.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Een [IAIConversation](../../com.aspose.slides/iaiconversation)-instantie.
### dispose() {#dispose--}
```
public final void dispose()
```


Libereert bronnen die door deze instantie worden gebruikt.