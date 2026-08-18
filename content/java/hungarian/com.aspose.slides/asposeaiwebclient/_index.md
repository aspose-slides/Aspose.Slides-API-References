---
title: AsposeAIWebClient
second_title: Aspose.Slides Java API hivatkozás
description: Beépített implementáció, amely az Aspose saját LLM-jéhez csatlakozik.
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

Egy beépített [IAIWebClient](../../com.aspose.slides/iaiwebclient) megvalósítás, amely az Aspose saját LLM-jéhez csatlakozik.  Ez az alapértelmezett kliens, amelyet a paraméter nélküli  SlidesAIAgent()  konstruktor használ.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Létrehoz egy példányt az Aspose AI webkliensből, amely az alapértelmezett Aspose LLM végponthoz csatlakozik. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Létrehoz egy példányt az Aspose AI webkliensből, amely az alapértelmezett Aspose LLM végponthoz csatlakozik egy külsőleg kezelt HttpURLConnection használatával. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Létrehoz egy példányt az Aspose AI webkliensből, amely egy egyedi végpont URL-hez csatlakozik. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Létrehoz egy példányt az Aspose AI webkliensből, amely egy egyedi végpont URL-hez csatlakozik egy külsőleg kezelt HttpURLConnection használatával. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Chatutasítást küld az AI modellnek, és visszaadja a válaszüzenetet a megadott utasításra. |
| [createConversation()](#createConversation--) | Létrehoz egy beszélgetés példányt. |
| [dispose()](#dispose--) | Felszabadítja az ezen példány által használt erőforrásokat. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Létrehoz egy példányt az Aspose AI webkliensből, amely az alapértelmezett Aspose LLM végponthoz csatlakozik.  Ez a kliens a paraméter nélküli  SlidesAIAgent()  konstruktor által használt, így expliciten csak akkor kell létrehozni, ha a klienst közvetlenül a  SlidesAIAgent(IAIWebClient)  konstruktorba szeretnénk átadni.

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

Létrehoz egy példányt az Aspose AI webkliensből, amely az alapértelmezett Aspose LLM végponthoz csatlakozik egy külsőleg kezelt HttpURLConnection használatával. A megadott HttpURLConnection-t ez a példány nem zárja le, és a hívó marad annak tulajdonosa.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Külsőleg kezelt HttpURLConnection példány. |

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

Létrehoz egy példányt az Aspose AI webkliensből, amely egy egyedi végpont URL-hez csatlakozik. Használd ezt a túlterhelést, ha az Aspose.Slides csapat által biztosított URL-t használod; ellenkező esetben használd a  AsposeAIWebClient()  túlterhelést az alapértelmezett URL-lel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Az Aspose LLM végpont URL-je, amelyet az Aspose.Slides csapat biztosít. |

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

Létrehoz egy példányt az Aspose AI webkliensből, amely egy egyedi végpont URL-hez csatlakozik egy külsőleg kezelt HttpURLConnection használatával. A megadott HttpURLConnection-t ez a példány nem zárja le, és a hívó marad annak tulajdonosa. Használd ezt a túlterhelést, ha az Aspose.Slides csapat által biztosított URL-t szeretnéd saját HttpURLConnection-oddal ellátni; ha csak a saját HttpURLConnection-t akarod az alapértelmezett URL-lel, akkor használd az AsposeAIWebClient(HttpURLConnection) túlterhelést.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Az Aspose LLM végpont URL-je, amelyet az Aspose.Slides csapat biztosít. |
| httpClient | java.net.HttpURLConnection | Külsőleg kezelt HttpURLConnection példány. |

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

Chatutasítást küld az AI modellnek, és visszaadja a válaszüzenetet a megadott utasításra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String | Az AI modell által feldolgozandó utasítás vagy üzenet. |

**Visszatérési érték:**
java.lang.String - Az AI modell által a megadott utasításra generált üzenet.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Létrehoz egy beszélgetés példányt. A szokásos AI hívásokkal ellentétben a beszélgetések megőrzik a teljes kontextust.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.

### dispose() {#dispose--}
```
public final void dispose()
```

Felszabadítja az ezen példány által használt erőforrásokat.