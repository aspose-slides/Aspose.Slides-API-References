---
title: OpenAICompatibleWebClient
second_title: Referencia de la API de Aspose.Slides para Java
description: Una implementación incorporada que se conecta a un proveedor LLM compatible con OpenAI en una URL base especificada.
type: docs
url: /es/com.aspose.slides/openaicompatiblewebclient/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Una implementación incorporada [IAIWebClient](../../com.aspose.slides/iaiwebclient) que se conecta a un proveedor LLM compatible con OpenAI en una URL base especificada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Creates an instance of the OpenAI-compatible web client. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the OpenAI-compatible web client that uses an externally managed  HttpURLConnection . |
## Métodos

| Método | Descripción |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using an externally managed HttpURLConnection instance and returns response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Crea una instancia del cliente web compatible con OpenAI.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Nombre del modelo soportado por el proveedor LLM. |
| apiKey | java.lang.String | Clave API (token). |
| baseUrl | java.lang.String | URL base del LLM compatible con OpenAI. |

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

Crea una instancia del cliente web compatible con OpenAI que utiliza un HttpURLConnection gestionado externamente. El HttpURLConnection proporcionado no es liberado por esta instancia y sigue siendo propiedad del llamador.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Nombre del modelo soportado por el proveedor LLM. |
| apiKey | java.lang.String | Clave API (token). |
| baseUrl | java.lang.String | URL base del LLM compatible con OpenAI. |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpURLConnection gestionada externamente. |

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

Envía una instrucción de chat al modelo de IA utilizando una instancia de HttpURLConnection gestionada externamente y devuelve el mensaje de respuesta a la instrucción proporcionada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instruction | java.lang.String | La instrucción o mensaje que será procesado por el modelo de IA. |

**Devuelve:**
java.lang.String - El mensaje generado por el modelo de IA en respuesta a la instrucción dada.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crea una instancia de conversación. A diferencia de las llamadas regulares a IA, las conversaciones conservan todo el contexto.

**Devuelve:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una instancia [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Libera los recursos utilizados por esta instancia.