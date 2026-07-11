---
title: OpenAIWebClient
second_title: Riferimento API Aspose.Slides per Java
description: Un'implementazione incorporata che si collega all'API OpenAI.
type: docs
url: /it/com.aspose.slides/openaiwebclient/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Un'implementazione [IAIWebClient](../../com.aspose.slides/iaiwebclient) incorporata che si collega all'API OpenAI.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crea un'istanza del client web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crea un'istanza del client web OpenAI che utilizza un HttpClient gestito esternamente. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crea un'istanza di conversazione. |
| [close()](#close--) | Rilascia le risorse utilizzate da questa istanza. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Crea un'istanza del client web OpenAI.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| model | java.lang.String | Modello linguistico OpenAI. Valori possibili: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Chiave API OpenAI. |
| organizationId | java.lang.String | ID organizzazione (opzionale). |
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

Crea un'istanza del client web OpenAI che utilizza un HttpClient gestito esternamente. L'HttpClient fornito non viene eliminato da questa istanza e rimane di proprietà del chiamante.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| model | java.lang.String | Modello linguistico OpenAI. Valori possibili: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Chiave API OpenAI |
| organizationId | java.lang.String | ID organizzazione (opzionale) |
| httpClient | java.net.HttpURLConnection | Un'istanza HttpClient gestita esternamente |
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

Invia un'istruzione di chat al modello AI usando un'istanza HttpConnection fornita e restituisce il messaggio di risposta all'istruzione data.

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

Crea un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni conservano l'intero contesto.

**Restituisce:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Un'istanza [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Rilascia le risorse utilizzate da questa istanza.