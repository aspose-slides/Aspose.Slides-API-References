---
title: OpenAICompatibleWebClient
second_title: Riferimento API di Aspose.Slides per Java
description: Un'implementazione integrata che si connette a un provider LLM compatibile con OpenAI a un URL di base specificato.
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

Una implementazione [IAIWebClient](../../com.aspose.slides/iaiwebclient) integrata che si connette a un provider LLM compatibile con OpenAI a un URL di base specificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crea un'istanza del client web compatibile con OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crea un'istanza del client web compatibile con OpenAI che utilizza un HttpClient gestito esternamente. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crea un'istanza di conversazione. |
| [dispose()](#dispose--) | Rilascia le risorse utilizzate da questa istanza. |
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
| baseUrl | java.lang.String | URL di base del LLM compatibile con OpenAI.

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


Crea un'istanza del client web compatibile con OpenAI che utilizza un HttpClient gestito esternamente. L'HttpClient fornito non viene eliminato da questa istanza e rimane di proprietà del chiamante.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| model | java.lang.String | Nome del modello supportato dal provider LLM. |
| apiKey | java.lang.String | Chiave API (token). |
| baseUrl | java.lang.String | URL di base del LLM compatibile con OpenAI. |
| httpClient | java.net.HttpURLConnection | Un'istanza di HttpClient gestita esternamente.

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