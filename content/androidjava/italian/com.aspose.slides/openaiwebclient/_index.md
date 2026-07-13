---
title: OpenAIWebClient
second_title: Riferimento API Java per Aspose.Slides per Android
description: Client web OpenAI leggero integrato
type: docs
url: /it/com.aspose.slides/openaiwebclient/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Client web OpenAI leggero incorporato
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crea un'istanza del client web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crea un'istanza del client web OpenAI. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Invia un'istruzione di chat al modello AI utilizzando un'istanza gestita esternamente e restituisce il messaggio di risposta all'istruzione data. |
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
| apiKey | java.lang.String | Chiave API OpenAI |
| organizationId | java.lang.String | ID organizzazione (opzionale) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


Crea un'istanza del client web OpenAI.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| model | java.lang.String | Modello linguistico OpenAI. Valori possibili: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Chiave API OpenAI |
| organizationId | java.lang.String | ID organizzazione (opzionale) |
| httpClient | java.net.HttpURLConnection | Un'istanza HttpURLConnection gestita esternamente. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Invia un'istruzione di chat al modello AI utilizzando un'istanza gestita esternamente e restituisce il messaggio di risposta all'istruzione data.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instruction | java.lang.String | L'istruzione o il messaggio da elaborare dal modello AI |

**Restituisce:**
java.lang.String - Il messaggio generato dal modello AI in risposta all'istruzione data.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Crea un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni mantengono l'intero contesto.

**Restituisce:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Un'[IAIConversation](../../com.aspose.slides/iaiconversation) istanza.
### close() {#close--}
```
public final void close()
```


Rilascia le risorse utilizzate da questa istanza.