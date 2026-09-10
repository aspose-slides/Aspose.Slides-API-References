---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides Androidhoz a Java API hivatkozásán keresztül
description: Beépített megvalósítás, amely egy megadott alap URL-re csatlakozik egy OpenAI-kompatibilis LLM szolgáltatóhoz.
type: docs
url: /hu/com.aspose.slides/openaicompatiblewebclient/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Egy beépített [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás, amely egy megadott alap URL-hez csatlakozik egy OpenAI-kompatibilis LLM szolgáltatóhoz.
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Létrehozza az OpenAI-kompatibilis webkliens egy példányát. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Létrehozza az OpenAI-kompatibilis webkliens egy példányát, amely egy külsőleg kezelt  HttpURLConnection . használ. |
## Methods

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Küld egy chat utasítást az AI modellnek egy külsőleg kezelt HttpURLConnection példány használatával, és visszaadja a válaszüzenetet a megadott utasításra. |
| [createConversation()](#createConversation--) | Létrehozza egy beszélgetés példányát. |
| [dispose()](#dispose--) | Felszabadítja az ezen példány által használt erőforrásokat. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```


Létrehozza az OpenAI-kompatibilis webkliens egy példányát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | Az LLM szolgáltató által támogatott modell neve. |
| apiKey | java.lang.String | API kulcs (token). |
| baseUrl | java.lang.String | Az OpenAI-kompatibilis LLM alap URL-je. |
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


Létrehozza az OpenAI-kompatibilis webkliens egy példányát, amely egy külsőleg kezelt  HttpURLConnection . használ. A megadott  HttpURLConnection  nincs felszabadítva ezen példány által, és a hívó birtokában marad.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | Az LLM szolgáltató által támogatott modell neve. |
| apiKey | java.lang.String | API kulcs (token). |
| baseUrl | java.lang.String | Az OpenAI-kompatibilis LLM alap URL-je. |
| httpClient | java.net.HttpURLConnection | Egy külsőleg kezelt  HttpURLConnection  példány. |
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


Küld egy chat utasítást az AI modellnek egy külsőleg kezelt HttpURLConnection példány használatával, és visszaadja a válaszüzenetet a megadott utasításra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String | Az AI modell által feldolgozandó utasítás vagy üzenet. |

**Visszatérési érték:**
java.lang.String - Az AI modell által az adott utasításra generált üzenet.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Létrehozza egy beszélgetés példányát. A szokásos AI hívásoktól eltérően a beszélgetések megőrzik a teljes kontextust.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.
### dispose() {#dispose--}
```
public final void dispose()
```


Felszabadítja az ezen példány által használt erőforrásokat.