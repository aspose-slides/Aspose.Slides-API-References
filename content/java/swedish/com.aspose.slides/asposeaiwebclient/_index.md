---
title: AsposeAIWebClient
second_title: Aspose.Slides för Java API-referens
description: En inbyggd implementation som ansluter till Asposes egna LLM.
type: docs
url: /sv/com.aspose.slides/asposeaiwebclient/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

En inbyggd [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementation som ansluter till Asposes egna LLM. Detta är standardklienten som används av den parameterlösa SlidesAIAgent()-konstruktorn.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Skapar en instans av Aspose AI-webbklienten som ansluter till standard-Aspose LLM-slutpunkten. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Skapar en instans av Aspose AI-webbklienten som ansluter till standard-Aspose LLM-slutpunkten med en externt hanterad HttpClient. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Skapar en instans av Aspose AI-webbklienten som ansluter till en anpassad slutpunkts-URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Skapar en instans av Aspose AI-webbklienten som ansluter till en anpassad slutpunkts-URL med en externt hanterad HttpClient. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Skapar en konversationsinstans. |
| [dispose()](#dispose--) | Frigör resurser som används av denna instans. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Skapar en instans av Aspose AI-webbklienten som ansluter till standard-Aspose LLM-slutpunkten. Detta är den klient som används av den parameterlösa SlidesAIAgent()-konstruktorn, så att skapa den explicit krävs endast när klienten skickas direkt till SlidesAIAgent(IAIWebClient)-konstruktorn.

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

Skapar en instans av Aspose AI-webbklienten som ansluter till standard-Aspose LLM-slutpunkten med en externt hanterad HttpClient. Den tillhandahållna HttpClient-instansen tas inte bort av denna instans och förblir ägd av anroparen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | En externt hanterad HttpClient-instans. |
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

Skapar en instans av Aspose AI-webbklienten som ansluter till en anpassad slutpunkts-URL. Använd denna överlagring när du har en URL som tillhandahålls av Aspose.Slides-teamet; annars, använd AsposeAIWebClient()-överlagringen med standard-URL.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Slutpunkts-URL för Aspose LLM, tillhandahållen av Aspose.Slides-teamet. |
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

Skapar en instans av Aspose AI-webbklienten som ansluter till en anpassad slutpunkts-URL med en externt hanterad HttpClient. Den tillhandahållna HttpClient-instansen tas inte bort av denna instans och förblir ägd av anroparen. Använd denna överlagring när du har en URL som tillhandahålls av Aspose.Slides-teamet och vill ange din egen HttpClient; om du bara behöver din egen HttpClient med standard-URL, använd AsposeAIWebClient(HttpClient)-överlagringen istället.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Slutpunkts-URL för Aspose LLM, tillhandahållen av Aspose.Slides-teamet. |
| httpClient | java.net.HttpURLConnection | En externt hanterad HttpClient-instans. |
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

Skickar en chattinstruktion till AI-modellen med en tillhandahållen HttpConnection-instans och returnerar svarmeddelandet för den givna instruktionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returnerar:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten.

**Returnerar:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - En [IAIConversation](../../com.aspose.slides/iaiconversation) instans.
### dispose() {#dispose--}
```
public final void dispose()
```

Frigör resurser som används av denna instans.