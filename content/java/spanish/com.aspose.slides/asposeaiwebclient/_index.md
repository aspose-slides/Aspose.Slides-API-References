---
title: AsposeAIWebClient
second_title: Referencia de API de Aspose.Slides para Java
description: Una implementación integrada que se conecta al LLM propio de Aspose.
type: docs
url: /es/com.aspose.slides/asposeaiwebclient/
---
**Herencia:**
java.lang.Object

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Una implementación [IAIWebClient](../../com.aspose.slides/iaiwebclient) incorporada que se conecta al LLM propio de Aspose. Este es el cliente predeterminado utilizado por el constructor sin parámetros  SlidesAIAgent()  .

## Constructores

| Constructor | Descripción |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Crea una instancia del cliente web Aspose AI que se conecta al punto final predeterminado de Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Crea una instancia del cliente web Aspose AI que se conecta al punto final predeterminado de Aspose LLM usando un HttpURLConnection  administrado externamente. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Crea una instancia del cliente web Aspose AI que se conecta a una URL de punto final personalizada. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Crea una instancia del cliente web Aspose AI que se conecta a una URL de punto final personalizada usando un HttpURLConnection  administrado externamente. |

## Métodos

| Método | Descripción |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envía una instrucción de chat al modelo de IA y devuelve el mensaje de respuesta a la instrucción dada. |
| [createConversation()](#createConversation--) | Crea una instancia de conversación. |
| [dispose()](#dispose--) | Libera los recursos utilizados por esta instancia. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Crea una instancia del cliente web Aspose AI que se conecta al punto final predeterminado de Aspose LLM. Este es el cliente utilizado por el constructor sin parámetros  SlidesAIAgent() , por lo que crearlo explícitamente solo es necesario cuando se pasa el cliente al constructor  SlidesAIAgent(IAIWebClient)  directamente.

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

Crea una instancia del cliente web Aspose AI que se conecta al punto final predeterminado de Aspose LLM usando un HttpURLConnection  administrado externamente. El  HttpURLConnection  proporcionado no es eliminado por esta instancia y sigue siendo propiedad del llamador.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpURLConnection  administrada externamente. |
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

Crea una instancia del cliente web Aspose AI que se conecta a una URL de punto final personalizada. Use esta sobrecarga cuando tenga una URL proporcionada por el equipo de Aspose.Slides; de lo contrario, use la sobrecarga  AsposeAIWebClient()  con la URL predeterminada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del punto final de Aspose LLM, proporcionada por el equipo de Aspose.Slides. |
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

Crea una instancia del cliente web Aspose AI que se conecta a una URL de punto final personalizada usando un HttpURLConnection  administrado externamente. El  HttpURLConnection  proporcionado no es eliminado por esta instancia y sigue siendo propiedad del llamador. Use esta sobrecarga cuando tenga una URL proporcionada por el equipo de Aspose.Slides y quiera suministrar su propio HttpURLConnection ; si solo necesita su propio HttpURLConnection  con la URL predeterminada, use la sobrecarga  AsposeAIWebClient(HttpURLConnection)  en su lugar.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del punto final de Aspose LLM, proporcionada por el equipo de Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpURLConnection  administrada externamente. |
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

Envía una instrucción de chat al modelo de IA y devuelve el mensaje de respuesta a la instrucción dada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instruction | java.lang.String | La instrucción o mensaje que debe procesar el modelo de IA. |

**Devuelve:**
java.lang.String - El mensaje generado por el modelo de IA en respuesta a la instrucción dada.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crea una instancia de conversación. A diferencia de las llamadas de IA regulares, las conversaciones conservan todo el contexto.

**Devuelve:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una instancia de [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Libera los recursos utilizados por esta instancia.