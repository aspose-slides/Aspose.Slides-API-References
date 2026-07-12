---
title: OpenAIWebClient
second_title: Referencia de API Java de Aspose.Slides para Android
description: Cliente web OpenAI liviano incorporado
type: docs
url: /es/com.aspose.slides/openaiwebclient/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Cliente web OpenAI liviano incorporado
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crea una instancia del cliente web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crea una instancia del cliente web OpenAI. |
## Métodos

| Método | Descripción |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envía una instrucción de chat al modelo de IA usando una instancia gestionada externamente y devuelve el mensaje de respuesta a la instrucción dada. |
| [createConversation()](#createConversation--) | Crea una instancia de conversación. |
| [close()](#close--) | Libera los recursos utilizados por esta instancia. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Crea una instancia del cliente web OpenAI.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Modelo de lenguaje OpenAI. Valores posibles: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clave API de OpenAI |
| organizationId | java.lang.String | ID de organización (opcional) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Crea una instancia del cliente web OpenAI.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Modelo de lenguaje OpenAI. Valores posibles: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clave API de OpenAI |
| organizationId | java.lang.String | ID de organización (opcional) |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpURLConnection gestionada externamente. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Envía una instrucción de chat al modelo de IA usando una instancia gestionada externamente y devuelve el mensaje de respuesta a la instrucción dada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instruction | java.lang.String | La instrucción o mensaje a ser procesado por el modelo de IA |

**Devuelve:**
java.lang.String - El mensaje generado por el modelo de IA en respuesta a la instrucción dada.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crea una instancia de conversación. A diferencia de las llamadas regulares a la IA, las conversaciones conservan todo el contexto.

**Devuelve:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una instancia de [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Libera los recursos utilizados por esta instancia.