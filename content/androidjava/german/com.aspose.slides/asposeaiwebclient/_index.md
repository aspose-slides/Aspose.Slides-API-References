---
title: AsposeAIWebClient
second_title: Aspose.Slides für Android über Java API Referenz
description: Eine eingebaute  Implementierung, die eine Verbindung zu Asposes eigenem LLM herstellt.
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

Eine eingebaute [IAIWebClient](../../com.aspose.slides/iaiwebclient) Implementierung, die eine Verbindung zu Asposes eigenem LLM herstellt. Dies ist der Standardclient, der vom parameterlosen SlidesAIAgent() Konstruktor verwendet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zum Standard-Aspose LLM Endpunkt herstellt. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zum Standard-Aspose LLM Endpunkt unter Verwendung einer extern verwalteten `HttpURLConnection` herstellt. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zu einer benutzerdefinierten Endpunkt-URL herstellt. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zu einer benutzerdefinierten Endpunkt-URL unter Verwendung einer extern verwalteten `HttpURLConnection` herstellt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sendet eine Chat-Anweisung an das KI-Modell und gibt die Antwortnachricht auf die gegebene Anweisung zurück. |
| [createConversation()](#createConversation--) | Erstellt eine Konversationsinstanz. |
| [dispose()](#dispose--) | Gibt die von dieser Instanz verwendeten Ressourcen frei. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```


Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zum Standard-Aspose LLM Endpunkt herstellt. Dies ist der Client, der vom parameterlosen SlidesAIAgent() Konstruktor verwendet wird, sodass eine explizite Erstellung nur nötig ist, wenn der Client direkt an den SlidesAIAgent(IAIWebClient) Konstruktor übergeben wird.

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


Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zum Standard-Aspose LLM Endpunkt unter Verwendung einer extern verwalteten `HttpURLConnection` herstellt. Die bereitgestellte `HttpURLConnection` wird von dieser Instanz nicht freigegeben und bleibt im Besitz des Aufrufers.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete `HttpURLConnection`-Instanz.

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


Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zu einer benutzerdefinierten Endpunkt-URL herstellt. Verwenden Sie diese Überladung, wenn Ihnen eine URL vom Aspose.Slides-Team bereitgestellt wurde; andernfalls verwenden Sie die AsposeAIWebClient() Überladung mit der Standard-URL.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Endpunkt-URL des Aspose LLM, bereitgestellt vom Aspose.Slides-Team.

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


Erstellt eine Instanz des Aspose AI Webclient, der eine Verbindung zu einer benutzerdefinierten Endpunkt-URL unter Verwendung einer extern verwalteten `HttpURLConnection` herstellt. Die bereitgestellte `HttpURLConnection` wird von dieser Instanz nicht freigegeben und bleibt im Besitz des Aufrufers. Verwenden Sie diese Überladung, wenn Ihnen eine URL vom Aspose.Slides-Team bereitgestellt wurde und Sie Ihre eigene `HttpURLConnection` bereitstellen möchten; falls Sie nur Ihre eigene `HttpURLConnection` mit der Standard-URL benötigen, verwenden Sie stattdessen die AsposeAIWebClient(HttpURLConnection) Überladung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Endpunkt-URL des Aspose LLM, bereitgestellt vom Aspose.Slides-Team. |
| httpClient | java.net.HttpURLConnection | Eine extern verwaltete `HttpURLConnection`-Instanz.

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


Sendet eine Chat-Anweisung an das KI-Modell und gibt die Antwortnachricht auf die gegebene Anweisung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instruction | java.lang.String | Die Anweisung oder Nachricht, die vom KI-Modell verarbeitet werden soll. |

**Rückgabe:**
java.lang.String - Die vom KI-Modell generierte Nachricht als Antwort auf die gegebene Anweisung.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Erstellt eine Konversationsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Unterhaltungen den gesamten Kontext.

**Rückgabe:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die von dieser Instanz verwendeten Ressourcen frei.