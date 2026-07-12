---
title: OpenAIWebClient
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Eingebauter leichter OpenAI-Webclient
type: docs
url: /de/com.aspose.slides/openaiwebclient/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Eingebauter leichter OpenAI-Webclient
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Erstellt eine Instanz des OpenAI-Webclients. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Erstellt eine Instanz des OpenAI-Webclients. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sendet eine Chat-Anweisung an das KI-Modell unter Verwendung einer extern verwalteten  Instanz und gibt die Antwortnachricht auf die gegebene Anweisung zurück. |
| [createConversation()](#createConversation--) | Erstellt eine Gesprächsinstanz. |
| [close()](#close--) | Gibt Ressourcen frei, die von dieser Instanz verwendet werden. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


Erstellt eine Instanz des OpenAI-Webclients.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| model | java.lang.String | OpenAI-Sprachmodell. Mögliche Werte: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI-API-Schlüssel |
| organizationId | java.lang.String | Organisations-ID (optional) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


Erstellt eine Instanz des OpenAI-Webclients.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| model | java.lang.String | OpenAI-Sprachmodell. Mögliche Werte: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI-API-Schlüssel |
| organizationId | java.lang.String | Organisations-ID (optional) |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete HttpURLConnection-Instanz. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Sendet eine Chat-Anweisung an das KI-Modell unter Verwendung einer extern verwalteten  Instanz und gibt die Antwortnachricht auf die gegebene Anweisung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instruction | java.lang.String | Die Anweisung oder Nachricht, die vom KI-Modell verarbeitet werden soll |

**Rückgabe:**
java.lang.String - Die vom KI-Modell generierte Nachricht als Antwort auf die gegebene Anweisung.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Erstellt eine Gesprächsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Gespräche den gesamten Kontext.

**Rückgabe:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Eine [IAIConversation](../../com.aspose.slides/iaiconversation)-Instanz.
### close() {#close--}
```
public final void close()
```


Gibt Ressourcen frei, die von dieser Instanz verwendet werden.