---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides för Java API-referens
description: En inbyggd implementation som ansluter till en OpenAI-kompatibel LLM-leverantör på en specificerad bas-URL.
type: docs
url: /sv/com.aspose.slides/openaicompatiblewebclient/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

En inbyggd [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementation som ansluter till en OpenAI-kompatibel LLM-leverantör på en specificerad bas-URL.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Skapar en instans av den OpenAI-kompatibla webbklienten. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Skapar en instans av den OpenAI-kompatibla webbklienten som använder en externt hanterad  HttpURLConnection . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Skickar en chattinstruktion till AI-modellen med en externt hanterad HttpURLConnection-instans och returnerar svarmeddelandet för den givna instruktionen. |
| [createConversation()](#createConversation--) | Skapar en konversationsinstans. |
| [dispose()](#dispose--) | Frigir resurser som används av denna instans. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```


Skapar en instans av den OpenAI-kompatibla webbklienten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| model | java.lang.String | Modellnamn som stöds av LLM-leverantören. |
| apiKey | java.lang.String | API-nyckel (token). |
| baseUrl | java.lang.String | Bas-URL för den OpenAI-kompatibla LLM.

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


Skapar en instans av den OpenAI-kompatibla webbklienten som använder en externt hanterad  HttpURLConnection . Den tillhandahållna  HttpURLConnection  frigörs inte av denna instans och förblir ägd av anroparen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| model | java.lang.String | Modellnamn som stöds av LLM-leverantören. |
| apiKey | java.lang.String | API-nyckel (token). |
| baseUrl | java.lang.String | Bas-URL för den OpenAI-kompatibla LLM. |
| httpClient | java.net.HttpURLConnection | En externt hanterad  HttpURLConnection  -instans.

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


Skickar en chattinstruktion till AI-modellen med en externt hanterad HttpURLConnection-instans och returnerar svarmeddelandet för den givna instruktionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String | Instruktionen eller meddelandet som ska bearbetas av AI-modellen. |

**Returnerar:**
java.lang.String - Meddelandet som genererats av AI-modellen som svar på den givna instruktionen.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten.

**Returnerar:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - En [IAIConversation](../../com.aspose.slides/iaiconversation)-instans.
### dispose() {#dispose--}
```
public final void dispose()
```


Frigir resurser som används av denna instans.