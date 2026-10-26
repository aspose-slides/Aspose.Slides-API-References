---
title: AsposeAIWebClient
second_title: Riferimento API di Aspose.Slides per Java
description: Un'implementazione integrata che si connette al LLM proprietario di Aspose.
type: docs
url: /it/com.aspose.slides/asposeaiwebclient/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Un'implementazione [IAIWebClient](../../com.aspose.slides/iaiwebclient) incorporata che si connette al LLM proprietario di Aspose. Questo è il client predefinito utilizzato dal costruttore senza parametri  SlidesAIAgent() .
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose utilizzando un HttpURLConnection gestito esternamente. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Crea un'istanza del client web Aspose AI che si connette a un URL di endpoint personalizzato. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Crea un'istanza del client web Aspose AI che si connette a un URL di endpoint personalizzato utilizzando un HttpURLConnection gestito esternamente. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Invia un'istruzione di chat al modello AI e restituisce il messaggio di risposta all'istruzione fornita. |
| [createConversation()](#createConversation--) | Crea un'istanza di conversazione. |
| [dispose()](#dispose--) | Rilascia le risorse utilizzate da questa istanza. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose. Questo è il client utilizzato dal costruttore senza parametri  SlidesAIAgent(), quindi crearne uno esplicitamente è necessario solo quando si passa il client direttamente al costruttore SlidesAIAgent(IAIWebClient).

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

Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose utilizzando un HttpURLConnection gestito esternamente. L'HttpURLConnection fornito non viene rilasciato da questa istanza e rimane di proprietà di chi chiama.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Un'istanza di HttpURLConnection gestita esternamente.

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

Crea un'istanza del client web Aspose AI che si connette a un URL di endpoint personalizzato. Usa questa overload quando hai un URL fornito dal team Aspose.Slides; altrimenti, utilizza l'overload AsposeAIWebClient() con l'URL predefinito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL endpoint del LLM Aspose, fornito dal team Aspose.Slides.

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

Crea un'istanza del client web Aspose AI che si connette a un URL di endpoint personalizzato utilizzando un HttpURLConnection gestito esternamente. L'HttpURLConnection fornito non viene rilasciato da questa istanza e rimane di proprietà di chi chiama. Usa questa overload quando hai un URL fornito dal team Aspose.Slides e vuoi fornire il tuo HttpURLConnection; se ti serve solo il tuo HttpURLConnection con l'URL predefinito, usa invece l'overload AsposeAIWebClient(HttpURLConnection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL endpoint del LLM Aspose, fornito dal team Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Un'istanza di HttpURLConnection gestita esternamente.

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

Invia un'istruzione di chat al modello AI e restituisce il messaggio di risposta all'istruzione fornita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instruction | java.lang.String | L'istruzione o il messaggio da elaborare dal modello AI. |

**Restituisce:**
java.lang.String - Il messaggio generato dal modello AI in risposta all'istruzione fornita.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crea un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni mantengono l'intero contesto.

**Restituisce:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una istanza [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Rilascia le risorse utilizzate da questa istanza.