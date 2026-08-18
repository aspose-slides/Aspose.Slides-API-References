---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides für Java API-Referenz
description: Eine eingebaute Implementierung, die sich mit einem OpenAI-kompatiblen LLM-Anbieter unter einer angegebenen Basis-URL verbindet.
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

Eine eingebaute [IAIWebClient](../../com.aspose.slides/iaiwebclient)-Implementierung, die sich mit einem OpenAI-kompatiblen LLM-Anbieter unter einer angegebenen Basis-URL verbindet.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Erstellt eine Instanz des OpenAI-kompatiblen Webclients. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Erstellt eine Instanz des OpenAI-kompatiblen Webclients, der ein extern verwaltetes HttpURLConnection verwendet. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sendet eine Chat-Anweisung an das KI-Modell unter Verwendung einer extern verwalteten HttpURLConnection-Instanz und gibt die Antwortnachricht zur angegebenen Anweisung zurück. |
| [createConversation()](#createConversation--) | Erstellt eine Konversationsinstanz. |
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

Erstellt eine Instanz des OpenAI-kompatiblen Webclients, der ein extern verwaltetes HttpURLConnection verwendet. Das bereitgestellte HttpURLConnection wird von dieser Instanz nicht freigegeben und bleibt im Besitz des Aufrufenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| model | java.lang.String | Modellname, der vom LLM-Anbieter unterstützt wird. |
| apiKey | java.lang.String | API-Schlüssel (Token). |
| baseUrl | java.lang.String | Basis-URL des OpenAI-kompatiblen LLM. |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete HttpURLConnection-Instanz. |

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

Sendet eine Chat-Anweisung an das KI-Modell unter Verwendung einer extern verwalteten HttpURLConnection-Instanz und gibt die Antwortnachricht zur angegebenen Anweisung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instruction | java.lang.String | Die Anweisung oder Nachricht, die vom KI-Modell verarbeitet werden soll. |

**Rückgabe:**
java.lang.String - Die vom KI-Modell als Antwort auf die angegebene Anweisung erzeugte Nachricht.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Erstellt eine Konversationsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Gespräche den gesamten Kontext.

**Rückgabe:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Eine [IAIConversation](../../com.aspose.slides/iaiconversation)-Instanz.
### dispose() {#dispose--}
```
public final void dispose()
```

Gibt Ressourcen frei, die von dieser Instanz verwendet werden.