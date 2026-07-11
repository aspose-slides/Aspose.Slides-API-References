---
title: AsposeAIWebClient
second_title: Aspose.Slides für Java API Referenz
description: Eine integrierte Implementierung, die eine Verbindung zu Asposes eigenem LLM herstellt.
type: docs
url: /de/com.aspose.slides/asposeaiwebclient/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Eine integrierte [IAIWebClient](../../com.aspose.slides/iaiwebclient)-Implementierung, die eine Verbindung zu Asposes eigenem LLM herstellt. Dies ist der Standard-Client, der vom parameterlosen  SlidesAIAgent() -Konstruktor verwendet wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Erstellt eine Instanz des Aspose-AI-Webclients, die eine Verbindung zum Standard-Aspose-LLM-Endpunkt herstellt. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Erstellt eine Instanz des Aspose-AI-Webclients, die unter Verwendung eines extern verwalteten HttpClient eine Verbindung zum Standard-Aspose-LLM-Endpunkt herstellt. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Erstellt eine Instanz des Aspose-AI-Webclients, die eine Verbindung zu einer benutzerdefinierten Endpunkt-URL herstellt. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Erstellt eine Instanz des Aspose-AI-Webclients, die unter Verwendung eines extern verwalteten HttpClient eine Verbindung zu einer benutzerdefinierten Endpunkt-URL herstellt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Erstellt eine Gesprächsinstanz. |
| [dispose()](#dispose--) | Gibt von dieser Instanz verwendete Ressourcen frei. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Erstellt eine Instanz des Aspose-AI-Webclients, die eine Verbindung zum Standard-Aspose-LLM-Endpunkt herstellt. Dies ist der Client, der vom parameterlosen  SlidesAIAgent() -Konstruktor verwendet wird, sodass das explizite Erstellen nur erforderlich ist, wenn der Client direkt an den  SlidesAIAgent(IAIWebClient) -Konstruktor übergeben wird.

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

Erstellt eine Instanz des Aspose-AI-Webclients, die unter Verwendung eines extern verwalteten HttpClient eine Verbindung zum Standard-Aspose-LLM-Endpunkt herstellt. Der bereitgestellte HttpClient wird von dieser Instanz nicht freigegeben und verbleibt im Besitz des Aufrufers.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete HttpClient-Instanz.

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

Erstellt eine Instanz des Aspose-AI-Webclients, die eine Verbindung zu einer benutzerdefinierten Endpunkt-URL herstellt. Verwenden Sie diese Überladung, wenn Sie eine von Aspose.Slides bereitgestellte URL haben; andernfalls verwenden Sie die  AsposeAIWebClient() -Überladung mit der Standard-URL.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Endpunkt-URL des Aspose-LLM, bereitgestellt vom Aspose.Slides-Team.

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

Erstellt eine Instanz des Aspose-AI-Webclients, die unter Verwendung eines extern verwalteten HttpClient eine Verbindung zu einer benutzerdefinierten Endpunkt-URL herstellt. Der bereitgestellte HttpClient wird von dieser Instanz nicht freigegeben und verbleibt im Besitz des Aufrufers. Verwenden Sie diese Überladung, wenn Sie eine von Aspose.Slides bereitgestellte URL haben und Ihren eigenen HttpClient bereitstellen möchten; wenn Sie nur Ihren eigenen HttpClient mit der Standard-URL benötigen, verwenden Sie stattdessen die  AsposeAIWebClient(HttpClient) -Überladung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Endpunkt-URL des Aspose-LLM, bereitgestellt vom Aspose.Slides-Team. |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete HttpClient-Instanz.

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

Erstellt eine Gesprächsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Unterhaltungen den gesamten Kontext.

**Rückgabewert:**
[IAIConversation](../../com.aspose.slides/iaiconversation) – eine [IAIConversation](../../com.aspose.slides/iaiconversation)-Instanz.

### dispose() {#dispose--}
```
public final void dispose()
```

Gibt von dieser Instanz verwendete Ressourcen frei.