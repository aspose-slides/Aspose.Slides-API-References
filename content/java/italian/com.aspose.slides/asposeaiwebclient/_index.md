---
title: AsposeAIWebClient
second_title: Riferimento API di Aspose.Slides per Java
description: Un'implementazione integrata che si connette al LLM proprietario di Aspose.
type: docs
url: /it/com.aspose.slides/asposeaiwebclient/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Un'implementazione [IAIWebClient](../../com.aspose.slides/iaiwebclient) integrata che si connette al LLM di Aspose. Questo è il client predefinito utilizzato dal costruttore SlidesAIAgent() senza parametri.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose utilizzando un HttpClient gestito esternamente. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Crea un'istanza del client web Aspose AI che si connette a un URL endpoint personalizzato. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Crea un'istanza del client web Aspose AI che si connette a un URL endpoint personalizzato utilizzando un HttpClient gestito esternamente. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crea un'istanza di conversazione. |
| [dispose()](#dispose--) | Rilascia le risorse utilizzate da questa istanza. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose. Questo è il client usato dal costruttore SlidesAIAgent() senza parametri, quindi crearne uno esplicitamente è necessario solo quando si passa il client al costruttore SlidesAIAgent(IAIWebClient) direttamente.

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

Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM Aspose utilizzando un HttpClient gestito esternamente. Il HttpClient fornito non viene eliminato da questa istanza e rimane di proprietà del chiamante.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Un'istanza di HttpClient gestita esternamente.

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

Crea un'istanza del client web Aspose AI che si connette a un URL endpoint personalizzato. Usa questa sovraccarico quando hai un URL fornito dal team Aspose.Slides; altrimenti, usa il sovraccarico AsposeAIWebClient() con l'URL predefinito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL endpoint del LLM Aspose, fornito dal team Aspose.Slides.

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

Crea un'istanza del client web Aspose AI che si connette a un URL endpoint personalizzato utilizzando un HttpClient gestito esternamente. Il HttpClient fornito non viene eliminato da questa istanza e rimane di proprietà del chiamante. Usa questa sovraccarico quando hai un URL fornito dal team Aspose.Slides e desideri fornire il tuo HttpClient; se hai bisogno solo del tuo HttpClient con l'URL predefinito, usa il sovraccarico AsposeAIWebClient(HttpClient).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL endpoint del LLM Aspose, fornito dal team Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Un'istanza di HttpClient gestita esternamente.

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

Invia un'istruzione di chat al modello AI utilizzando un'istanza HttpConnection fornita e restituisce il messaggio di risposta all'istruzione data.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Restituisce:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crea un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni mantengono l'intero contesto.

**Restituisce:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Un'istanza [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Rilascia le risorse utilizzate da questa istanza.