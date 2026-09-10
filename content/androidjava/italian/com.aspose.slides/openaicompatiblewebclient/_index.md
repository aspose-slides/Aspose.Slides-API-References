---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides per Android via Riferimento API Java
description: Un'implementazione integrata che si connette a un provider LLM compatibile con OpenAI a un URL base specificato.
type: docs
url: /it/com.aspose.slides/openaicompatiblewebclient/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Un'implementazione [IAIWebClient](../../com.aspose.slides/iaiwebclient) integrata che si connette a un provider LLM compatibile con OpenAI a un URL base specificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Creates an instance of the OpenAI-compatible web client. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the OpenAI-compatible web client that uses an externally managed  HttpURLConnection . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using an externally managed HttpURLConnection instance and returns response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Crea un'istanza del client web compatibile con OpenAI.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| model | java.lang.String | Nome del modello supportato dal provider LLM. |
| apiKey | java.lang.String | Chiave API (token). |
| baseUrl | java.lang.String | URL di base del LLM compatibile con OpenAI. |
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

Crea un'istanza del client web compatibile con OpenAI che utilizza un HttpURLConnection gestito esternamente. L'HttpURLConnection fornito non viene rilasciato da questa istanza e rimane di proprietà del chiamante.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| model | java.lang.String | Nome del modello supportato dal provider LLM. |
| apiKey | java.lang.String | Chiave API (token). |
| baseUrl | java.lang.String | URL di base del LLM compatibile con OpenAI. |
| httpClient | java.net.HttpURLConnection | Un'istanza HttpURLConnection gestita esternamente. |
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

Invia un'istruzione di chat al modello AI utilizzando un'istanza HttpURLConnection gestita esternamente e restituisce il messaggio di risposta all'istruzione fornita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instruction | java.lang.String | L'istruzione o il messaggio da elaborare dal modello AI. |

**Restituisce:**
java.lang.String - Il messaggio generato dal modello AI in risposta all'istruzione fornita.
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Crea un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni conservano l'intero contesto.

**Restituisce:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una istanza [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Rilascia le risorse utilizzate da questa istanza.