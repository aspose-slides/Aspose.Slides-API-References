---
title: OpenAIWebClient
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Beépített könnyűsúlyú OpenAI webkliens
type: docs
url: /hu/com.aspose.slides/openaiwebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Beépített könnyűsúlyú OpenAI webkliens
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Létrehozza az OpenAI Web kliens példányát. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Létrehozza az OpenAI Web kliens példányát. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Chatutasítást küld az AI modellnek egy külsőleg kezelt példány használatával, és visszaadja a válaszüzenetet a megadott utasításra. |
| [createConversation()](#createConversation--) | Létrehozza egy beszélgetés példányát. |
| [close()](#close--) | Felszabadítja az ezen példány által használt erőforrásokat. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Létrehozza az OpenAI Web kliens példányát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | OpenAI nyelvi modell. Lehetséges értékek: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API kulcs |
| organizationId | java.lang.String | Szervezeti azonosító (opcionális) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


Létrehozza az OpenAI Web kliens példányát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| model | java.lang.String | OpenAI nyelvi modell. Lehetséges értékek: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API kulcs |
| organizationId | java.lang.String | Szervezeti azonosító (opcionális) |
| httpClient | java.net.HttpURLConnection | Egy külsőleg kezelt HttpURLConnection példány. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Chatutasítást küld az AI modellnek egy külsőleg kezelt példány használatával, és visszaadja a válaszüzenetet a megadott utasításra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String | Az AI modell által feldolgozandó utasítás vagy üzenet |

**Visszatérési érték:**
java.lang.String - Az AI modell által a megadott utasításra generált üzenet.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Létrehozza egy beszélgetés példányát. A normál AI hívásokkal ellentétben a beszélgetések megtartják a teljes kontextust.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.

### close() {#close--}
```
public final void close()
```


Felszabadítja az ezen példány által használt erőforrásokat.