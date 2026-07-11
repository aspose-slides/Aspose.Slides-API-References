---
title: OpenAIWebClient
second_title: Aspose.Slides für Java API-Referenz
description: Eine eingebaute Implementierung, die eine Verbindung zur OpenAI-API herstellt.
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

Eine eingebaute [IAIWebClient](../../com.aspose.slides/iaiwebclient) Implementierung, die eine Verbindung zur OpenAI-API herstellt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Erstellt eine Instanz des OpenAI-Webclients. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Erstellt eine Instanz des OpenAI-Webclients, die einen extern verwalteten HttpClient verwendet. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Erstellt eine Konversationsinstanz. |
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
| apiKey | java.lang.String | OpenAI-API-Schlüssel. |
| organizationId | java.lang.String | Organisations-ID (optional). |

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Erstellt eine Instanz des OpenAI-Webclients, die einen extern verwalteten HttpClient verwendet. Der bereitgestellte HttpClient wird von dieser Instanz nicht freigegeben und verbleibt beim Aufrufer.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| model | java.lang.String | OpenAI-Sprachmodell. Mögliche Werte: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI-API-Schlüssel |
| organizationId | java.lang.String | Organisations-ID (optional) |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete HttpClient-Instanz |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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

Sendet eine Chat-Anweisung an das KI-Modell unter Verwendung einer bereitgestellten HttpConnection-Instanz und gibt die Antwortnachricht zur angegebenen Anweisung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Rückgabewert:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Erstellt eine Konversationsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Gespräche den gesamten Kontext bei.

**Rückgabewert:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Eine [IAIConversation](../../com.aspose.slides/iaiconversation) Instanz.
### close() {#close--}
```
public final void close()
```

Gibt Ressourcen frei, die von dieser Instanz verwendet werden.