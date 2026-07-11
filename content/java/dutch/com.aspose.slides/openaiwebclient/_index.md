---
title: OpenAIWebClient
second_title: Aspose.Slides voor Java API-referentie
description: Een ingebouwde implementatie die verbinding maakt met de OpenAI API.
type: docs
url: /nl/com.aspose.slides/openaiwebclient/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Een ingebouwde [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementatie die verbinding maakt met de OpenAI-API.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Maakt een instantie van de OpenAI-webclient. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Maakt een instantie van de OpenAI-webclient die een extern beheerde  HttpClient  gebruikt. |
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Maakt een gesprek-instantie. |
| [close()](#close--) | Vrijgeeft de door deze instantie gebruikte bronnen. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Maakt een instantie van de OpenAI-webclient.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| model | java.lang.String | OpenAI-taalmodel. Mogelijke waarden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI-API-sleutel. |
| organizationId | java.lang.String | Organisatie-ID (optioneel). |

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


Maakt een instantie van de OpenAI-webclient die een extern beheerde  HttpClient  gebruikt. De meegeleverde  HttpClient  wordt niet door deze instantie verwijderd en blijft eigendom van de aanroeper.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| model | java.lang.String | OpenAI-taalmodel. Mogelijke waarden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI-API-sleutel |
| organizationId | java.lang.String | Organisatie-ID (optioneel) |
| httpClient | java.net.HttpURLConnection | Een extern beheerde HttpClient-instantie |

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


Verzendt een chat-instructie naar het AI-model met een meegeleverde HttpConnection-instantie en retourneert het antwoordbericht op de gegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Retourneert:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Maakt een gesprek-instantie. In tegenstelling tot reguliere AI-oproepen behouden gesprekken de volledige context.

**Retourneert:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Een [IAIConversation](../../com.aspose.slides/iaiconversation)-instantie.
### close() {#close--}
```
public final void close()
```


Vrijgeeft de door deze instantie gebruikte bronnen.