---
title: AsposeAIWebClient
second_title: Aspose.Slides voor Java API-referentie
description: Een ingebouwde implementatie die verbinding maakt met Aspose's eigen LLM.
type: docs
url: /nl/com.aspose.slides/asposeaiwebclient/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Een ingebouwde [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementatie die verbinding maakt met het eigen LLM van Aspose. Dit is de standaardclient die wordt gebruikt door de parameterloze  SlidesAIAgent()  constructor.

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt met een extern beheerde HttpClient. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL met een extern beheerde HttpClient. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Maakt een gespreks-instantie. |
| [dispose()](#dispose--) | Vrijgeeft bronnen die door deze instantie worden gebruikt. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt. Dit is de client die wordt gebruikt door de parameterloze  SlidesAIAgent()  constructor, dus het expliciet aanmaken is alleen nodig wanneer de client rechtstreeks wordt doorgegeven aan de  SlidesAIAgent(IAIWebClient)  constructor.

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

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt met een extern beheerde HttpClient. De doorgegeven HttpClient wordt niet door deze instantie vrijgegeven en blijft eigendom van de aanroeper.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Een extern beheerde HttpClient-instantie. |
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

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL. Gebruik deze overload wanneer u een URL heeft die door het Aspose.Slides-team wordt geleverd; anders gebruikt u de  AsposeAIWebClient()  overload met de standaard-URL.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | Eindpunt-URL van de Aspose LLM, geleverd door het Aspose.Slides-team. |
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

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL met een extern beheerde HttpClient. De doorgegeven HttpClient wordt niet door deze instantie vrijgegeven en blijft eigendom van de aanroeper. Gebruik deze overload wanneer u een URL heeft die door het Aspose.Slides-team wordt geleverd en u uw eigen HttpClient wilt gebruiken; als u alleen uw eigen HttpClient nodig heeft met de standaard-URL, gebruik dan de AsposeAIWebClient(HttpClient) overload.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | Eindpunt-URL van de Aspose LLM, geleverd door het Aspose.Slides-team. |
| httpClient | java.net.HttpURLConnection | Een extern beheerde HttpClient-instantie. |
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

Stuur een chat-instructie naar het AI-model met behulp van een verstrekte HttpConnection-instantie en retourneer het responsbericht voor de opgegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Retourwaarde:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Maakt een gespreks-instantie. In tegenstelling tot reguliere AI-aanroepen behouden gesprekken de volledige context.

[IAIConversation](../../com.aspose.slides/iaiconversation) - Een [IAIConversation](../../com.aspose.slides/iaiconversation) instantie.

### dispose() {#dispose--}
```
public final void dispose()
```

Vrijgeeft bronnen die door deze instantie worden gebruikt.