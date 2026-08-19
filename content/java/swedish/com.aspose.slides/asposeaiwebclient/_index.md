---
title: AsposeAIWebClient
second_title: Aspose.Slides för Java API-referens
description: En inbyggd implementation som ansluter till Asposes egen LLM.
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

En inbyggd [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementation som ansluter till Asposes egen LLM. Detta är standardklienten som används av den parameterlösa SlidesAIAgent()-konstruktorn.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Skapar en instans av Aspose AI web client som ansluter till standard Aspose LLM-slutpunkt. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Skapar en instans av Aspose AI web client som ansluter till standard Aspose LLM-slutpunkt med en externt hanterad  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Skapar en instans av Aspose AI web client som ansluter till en anpassad endpoint URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Skapar en instans av Aspose AI web client som ansluter till en anpassad endpoint URL med en externt hanterad  HttpURLConnection . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Skickar en chatinstruktion till AI-modellen och returnerar svarmeddelandet för den givna instruktionen. |
| [createConversation()](#createConversation--) | Skapar en konversationsinstans. |
| [dispose()](#dispose--) | Frigir resurser som används av denna instans. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Skapar en instans av Aspose AI web client som ansluter till standard Aspose LLM-slutpunkt. Detta är klienten som används av den parameterlösa SlidesAIAgent()-konstruktorn, så att skapa den explicit krävs endast när klienten skickas direkt till SlidesAIAgent(IAIWebClient)-konstruktorn.

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

Skapar en instans av Aspose AI web client som ansluter till standard Aspose LLM-slutpunkt med en externt hanterad  HttpURLConnection . Den tillhandahållna HttpURLConnection-disposeras inte av denna instans och förblir ägd av anroparen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | En externt hanterad  HttpURLConnection  instans.

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

Skapar en instans av Aspose AI web client som ansluter till en anpassad endpoint-URL. Använd detta överlagringsalternativ när du har en URL som tillhandahålls av Aspose.Slides-teamet; annars, använd AsposeAIWebClient()-överlagringen med standard-URL.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Endpoint-URL för Aspose LLM, tillhandahållen av Aspose.Slides-teamet.

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

Skapar en instans av Aspose AI web client som ansluter till en anpassad endpoint-URL med en externt hanterad  HttpURLConnection . Den tillhandahållna HttpURLConnection-disposeras inte av denna instans och förblir ägd av anroparen. Använd detta överlagringsalternativ när du har en URL som tillhandahålls av Aspose.Slides-teamet och vill tillhandahålla din egen HttpURLConnection; om du bara behöver din egen HttpURLConnection med standard-URL, använd istället AsposeAIWebClient(HttpURLConnection)-överlagringen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Endpoint-URL för Aspose LLM, tillhandahållen av Aspose.Slides-teamet. |
| httpClient | java.net.HttpURLConnection | En externt hanterad  HttpURLConnection  instans.

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

Skickar en chatinstruktion till AI-modellen och returnerar svarmeddelandet för den givna instruktionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String | Instruktionen eller meddelandet som ska bearbetas av AI-modellen. |

**Returvärde:**
java.lang.String - Meddelandet som genererats av AI-modellen som svar på den givna instruktionen.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten.

**Returvärde:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - En [IAIConversation](../../com.aspose.slides/iaiconversation)-instans.
### dispose() {#dispose--}
```
public final void dispose()
```

Frigir resurser som används av denna instans.