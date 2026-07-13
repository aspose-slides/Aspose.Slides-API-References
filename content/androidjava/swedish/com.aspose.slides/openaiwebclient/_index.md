---
title: OpenAIWebClient
second_title: Aspose.Slides för Android via Java API-referens
description: Inbyggd lättviktig OpenAI-webbklient
type: docs
url: /sv/com.aspose.slides/openaiwebclient/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Inbyggd lättviktig OpenAI-webklient
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Skapar en instans av OpenAI Web-klienten. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Skapar en instans av OpenAI Web-klienten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Skickar en chattinstruktion till AI-modellen med en externt hanterad  instans och returnerar svarmeddelandet till den givna instruktionen. |
| [createConversation()](#createConversation--) | Skapar en konversationsinstans. |
| [close()](#close--) | Frigör resurser som används av denna instans. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Skapar en instans av OpenAI Web-klienten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| model | java.lang.String | OpenAI-språkmodell. Möjliga värden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API-nyckel |
| organizationId | java.lang.String | Organisations-ID (valfritt) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Skapar en instans av OpenAI Web-klienten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| model | java.lang.String | OpenAI-språkmodell. Möjliga värden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API-nyckel |
| organizationId | java.lang.String | Organisations-ID (valfritt) |
| httpClient | java.net.HttpURLConnection | En externt hanterad HttpURLConnection-instans. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Skickar en chattinstruktion till AI-modellen med en externt hanterad  instans och returnerar svarmeddelandet till den givna instruktionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String | Instruktionen eller meddelandet som ska bearbetas av AI-modellen |

**Returnerar:**
java.lang.String - Meddelandet som genererats av AI-modellen som svar på den givna instruktionen.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten.

**Returnerar:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - En [IAIConversation](../../com.aspose.slides/iaiconversation)-instans.
### close() {#close--}
```
public final void close()
```

Frigör resurser som används av denna instans.