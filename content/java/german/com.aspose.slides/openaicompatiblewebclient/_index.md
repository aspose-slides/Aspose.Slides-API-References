---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides für Java API-Referenz
description: Eine eingebaute Implementierung, die eine Verbindung zu einem OpenAI-kompatiblen LLM-Anbieter unter einer angegebenen Basis-URL herstellt.
type: docs
url: /de/com.aspose.slides/openaicompatiblewebclient/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Eine eingebaute [IAIWebClient](../../com.aspose.slides/iaiwebclient) Implementierung, die eine Verbindung zu einem OpenAI-kompatiblen LLM-Anbieter unter einer angegebenen Basis-URL herstellt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Erstellt eine Instanz des OpenAI-kompatiblen Webclients. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Erstellt eine Instanz des OpenAI-kompatiblen Webclients, der einen extern verwalteten  HttpClient  verwendet. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Erstellt eine Gesprächsinstanz. |
| [dispose()](#dispose--) | Gibt Ressourcen frei, die von dieser Instanz verwendet werden. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Erstellt eine Instanz des OpenAI-kompatiblen Webclients.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| model | java.lang.String | Modellname, der vom LLM-Anbieter unterstützt wird. |
| apiKey | java.lang.String | API-Schlüssel (Token). |
| baseUrl | java.lang.String | Basis-URL des OpenAI-kompatiblen LLM. |
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

Erstellt eine Instanz des OpenAI-kompatiblen Webclients, der einen extern verwalteten  HttpClient  verwendet. Der bereitgestellte  HttpClient  wird von dieser Instanz nicht freigegeben und bleibt im Besitz des Aufrufenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| model | java.lang.String | Modellname, der vom LLM-Anbieter unterstützt wird. |
| apiKey | java.lang.String | API-Schlüssel (Token). |
| baseUrl | java.lang.String | Basis-URL des OpenAI-kompatiblen LLM. |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete  HttpClient  Instanz. |
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

Erstellt eine Gesprächsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Gespräche den gesamten Kontext bei.

**Rückgabewert:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Eine [IAIConversation](../../com.aspose.slides/iaiconversation) Instanz.
### dispose() {#dispose--}
```
public final void dispose()
```

Gibt Ressourcen frei, die von dieser Instanz verwendet werden.