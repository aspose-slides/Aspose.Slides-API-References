---
title: OpenAIWebClient
second_title: Aspose.Slides voor Android via Java API-referentie
description: Ingebouwde lichtgewicht OpenAI webclient
type: docs
url: /nl/com.aspose.slides/openaiwebclient/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Ingebouwde lichtgewicht OpenAI-webclient
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Maakt een instantie van OpenAI Web client. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Maakt een instantie van OpenAI Web client. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Stuurt een chatinstructie naar het AI-model met behulp van een extern beheerde instantie en retourneert het reactiebericht op de gegeven instructie. |
| [createConversation()](#createConversation--) | Maakt een conversatie-instantie. |
| [close()](#close--) | Vrijgeeft de resources die door deze instantie worden gebruikt. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Maakt een instantie van OpenAI Web client.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| model | java.lang.String | OpenAI-taalmodel. Mogelijke waarden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API-sleutel |
| organizationId | java.lang.String | Organisatie-ID (optioneel) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Maakt een instantie van OpenAI Web client.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| model | java.lang.String | OpenAI-taalmodel. Mogelijke waarden: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API-sleutel |
| organizationId | java.lang.String | Organisatie-ID (optioneel) |
| httpClient | java.net.HttpURLConnection | Een extern beheerde HttpURLConnection-instantie. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Stuurt een chatinstructie naar het AI-model met behulp van een extern beheerde instantie en retourneert het reactiebericht op de gegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String | De instructie of het bericht dat door het AI-model moet worden verwerkt. |

**Returns:**
java.lang.String - Het bericht dat door het AI-model wordt gegenereerd als reactie op de gegeven instructie.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Maakt een conversatie-instantie. In tegenstelling tot reguliere AI-aanroepen behouden gesprekken de volledige context.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Een [IAIConversation](../../com.aspose.slides/iaiconversation) instantie.
### close() {#close--}
```
public final void close()
```

Vrijgeeft de resources die door deze instantie worden gebruikt.