---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides för Java API-referens
description: En inbyggd implementation som ansluter till en OpenAI-kompatibel LLM-leverantör på en specificerad grund-URL.
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

En inbyggd [IAIWebClient](../../com.aspose.slides/iaiwebclient)-implementation som ansluter till en OpenAI-kompatibel LLM-leverantör på en angiven grund-URL.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Skapar en instans av den OpenAI-kompatibla webbklienten. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Skapar en instans av den OpenAI-kompatibla webbklienten som använder en externt hanterad  HttpClient . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
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
| baseUrl | java.lang.String | Grund-URL för den OpenAI-kompatibla LLM:n.

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


Skapar en instans av den OpenAI-kompatibla webbklienten som använder en externt hanterad HttpClient. Den tillhandahållna HttpClienten disponeras inte av denna instans och förblir ägd av anroparen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| model | java.lang.String | Modellnamn som stöds av LLM-leverantören. |
| apiKey | java.lang.String | API-nyckel (token). |
| baseUrl | java.lang.String | Grund-URL för den OpenAI-kompatibla LLM:n. |
| httpClient | java.net.HttpURLConnection | En externt hanterad HttpClient-instans.

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


Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela sammanhanget.

**Returnerar:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - En [IAIConversation](../../com.aspose.slides/iaiconversation) instans.
### dispose() {#dispose--}
```
public final void dispose()
```


Frigir resurser som används av denna instans.