---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides Java API referencia
description: Beépített megvalósítás, amely megadott alap URL-en keresztül csatlakozik egy OpenAI-kompatibilis LLM szolgáltatóhoz.
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

Beépített [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás, amely egy megadott alap URL-en keresztül csatlakozik egy OpenAI-kompatibilis LLM szolgáltatóhoz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Létrehoz egy példányt a OpenAI-kompatibilis webkliensből. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Létrehoz egy példányt a OpenAI-kompatibilis webkliensből, amely egy külsőleg kezelt HttpURLConnection-t használ. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Chatutasítást küld a AI modellnek egy külsőleg kezelt HttpURLConnection példány használatával, és visszaadja a válaszüzenetet az adott utasításra. |
| [createConversation()](#createConversation--) | Létrehoz egy beszélgetés példányt. |
| [dispose()](#dispose--) | Felszabadítja az ezen példány által használt erőforrásokat. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Létrehoz egy példányt a OpenAI-kompatibilis webkliensből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | A LLM szolgáltató által támogatott modell neve. |
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

Létrehoz egy példányt a OpenAI-kompatibilis webkliensből, amely egy külsőleg kezelt HttpURLConnection-t használ. A megadott HttpURLConnection-t ez a példány nem állítja le, és a hívó marad a tulajdonosa.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | A LLM szolgáltató által támogatott modell neve. |
| apiKey | java.lang.String | API kulcs (token). |
| baseUrl | java.lang.String | Az OpenAI-kompatibilis LLM alap URL-je. |
| httpClient | java.net.HttpURLConnection | Egy külsőleg kezelt HttpURLConnection példány. |

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

Chatutasítást küld a AI modellnek egy külsőleg kezelt HttpURLConnection példány használatával, és visszaadja a válaszüzenetet az adott utasításra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String | Az AI modell által feldolgozandó utasítás vagy üzenet. |

**Visszatérési érték:**
java.lang.String - A megadott utasításra a AI modell által generált üzenet.
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Létrehoz egy beszélgetés példányt. A normál AI hívásoktól eltérően a beszélgetések megőrzik a teljes kontextust.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.
### dispose() {#dispose--}
```
public final void dispose()
```

Felszabadítja az ezen példány által használt erőforrásokat.