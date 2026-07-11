---
title: AsposeAIWebClient
second_title: Aspose.Slides Java API referencia
description: Beépített megvalósítás, amely az Aspose saját LLM-jéhez csatlakozik.
type: docs
url: /hu/com.aspose.slides/asposeaiwebclient/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Egy beépített [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás, amely az Aspose saját LLM-jéhez csatlakozik. Ez az alapértelmezett kliens, amelyet a paraméter nélküli  SlidesAIAgent()  konstruktor használ.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Létrehozza az Aspose AI webkliens egy példányát, amely a alapértelmezett Aspose LLM végponthoz csatlakozik. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Létrehozza az Aspose AI webkliens egy példányát, amely a alapértelmezett Aspose LLM végponthoz csatlakozik egy külsőleg kezelt HttpClient használatával. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Létrehozza az Aspose AI webkliens egy példányát, amely egy egyéni végpont URL-hez csatlakozik. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Létrehozza az Aspose AI webkliens egy példányát, amely egy egyéni végpont URL-hez csatlakozik egy külsőleg kezelt HttpClient használatával. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Létrehoz egy beszélgetéspéldányt. |
| [dispose()](#dispose--) | Felszabadítja az ezen példány által használt erőforrásokat. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Létrehozza az Aspose AI webkliens egy példányát, amely a alapértelmezett Aspose LLM végponthoz csatlakozik. Ez a kliens a paraméter nélküli SlidesAIAgent() konstruktor által használt, így explicit módon csak akkor szükséges létrehozni, ha a klienst közvetlenül a SlidesAIAgent(IAIWebClient) konstruktorba adjuk át.

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

Létrehozza az Aspose AI webkliens egy példányát, amely a alapértelmezett Aspose LLM végponthoz csatlakozik egy külsőleg kezelt HttpClient használatával. A biztosított HttpClient-et ez a példány nem zárja le, és a hívó marad a tulajdonosa.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Külsőleg kezelt HttpClient példány.

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

Létrehozza az Aspose AI webkliens egy példányát, amely egy egyéni végpont URL-hez csatlakozik. Ezt a túlterhelést akkor használja, ha az Aspose.Slides csapat által megadott URL-vel rendelkezik; egyébként használja az AsposeAIWebClient() túlterhelést az alapértelmezett URL-lel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Az Aspose LLM végpont URL-je, amelyet az Aspose.Slides csapat biztosít.

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

Létrehozza az Aspose AI webkliens egy példányát, amely egy egyéni végpont URL-hez csatlakozik egy külsőleg kezelt HttpClient használatával. A biztosított HttpClient-et ez a példány nem zárja le, és a hívó marad a tulajdonosa. Ezt a túlterhelést akkor használja, ha az Aspose.Slides csapat által megadott URL-vel rendelkezik, és saját HttpClient-et szeretne biztosítani; ha csak a saját HttpClient-re van szüksége az alapértelmezett URL-lel, használja az AsposeAIWebClient(HttpClient) túlterhelést.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Az Aspose LLM végpont URL-je, amelyet az Aspose.Slides csapat biztosít. |
| httpClient | java.net.HttpURLConnection | Külsőleg kezelt HttpClient példány.

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

Egy csevegési utasítást küld az AI modellnek a megadott HttpConnection példány használatával, és visszaadja a válaszüzenetet az adott utasításra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Visszatérési érték:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Létrehoz egy beszélgetéspéldányt. A normál AI hívásokhoz képest a beszélgetések az egész kontextust megtartják.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.
### dispose() {#dispose--}
```
public final void dispose()
```

Felszabadítja az ezen példány által használt erőforrásokat.