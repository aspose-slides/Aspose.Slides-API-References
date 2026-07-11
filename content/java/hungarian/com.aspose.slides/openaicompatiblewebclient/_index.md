---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides Java API Referenciája
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

Beépített [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás, amely egy megadott alap URL-n keresztül csatlakozik egy OpenAI-kompatibilis LLM szolgáltatóhoz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Létrehoz egy példányt az OpenAI-kompatibilis webkliensből. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Létrehoz egy példányt az OpenAI-kompatibilis webkliensből, amely egy külsőleg kezelt HttpClient-et használ. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Létrehoz egy beszélgetés példányt. |
| [dispose()](#dispose--) | Felszabadítja a példány által használt erőforrásokat. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Létrehoz egy példányt az OpenAI-kompatibilis webkliensből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | A LLM szolgáltató által támogatott modell neve. |
| apiKey | java.lang.String | API kulcs (token). |
| baseUrl | java.lang.String | Az OpenAI-kompatibilis LLM alap URL-je. |

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

Létrehoz egy példányt az OpenAI-kompatibilis webkliensből, amely egy külsőleg kezelt HttpClient-et használ. A megadott HttpClient-et ez a példány nem zárja le, és a hívó fenntartja annak tulajdonjogát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | A LLM szolgáltató által támogatott modell neve. |
| apiKey | java.lang.String | API kulcs (token). |
| baseUrl | java.lang.String | Az OpenAI-kompatibilis LLM alap URL-je. |
| httpClient | java.net.HttpURLConnection | Egy külsőleg kezelt HttpClient példány. |

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

Chat utasítást küld a mesterséges intelligencia modellnek egy megadott HttpConnection példány használatával, és visszaküldi a válaszüzenetet a megadott utasításhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Visszatérési érték:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Létrehoz egy beszélgetés példányt. A szokásos AI hívásokkal szemben a beszélgetések megtartják az egész kontextust.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.
### dispose() {#dispose--}
```
public final void dispose()
```

Felszabadítja a példány által használt erőforrásokat.