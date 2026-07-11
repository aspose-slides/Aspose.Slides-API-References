---
title: AsposeAIWebClient
second_title: Referencia de API de Aspose.Slides para Java
description: Una implementación incorporada que se conecta al LLM propio de Aspose.
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

Una implementación [IAIWebClient](../../com.aspose.slides/iaiwebclient) incorporada que se conecta al LLM propio de Aspose. Este es el cliente predeterminado usado por el constructor sin parámetros  SlidesAIAgent()  constructor.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Crea una instancia del cliente web Aspose AI que se conecta al endpoint predeterminado de Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Crea una instancia del cliente web Aspose AI que se conecta al endpoint predeterminado de Aspose LLM usando un HttpClient gestionado externamente. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Crea una instancia del cliente web Aspose AI que se conecta a una URL de endpoint personalizada. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Crea una instancia del cliente web Aspose AI que se conecta a una URL de endpoint personalizada usando un HttpClient gestionado externamente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crea una instancia de conversación. |
| [dispose()](#dispose--) | Libera los recursos utilizados por esta instancia. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Crea una instancia del cliente web Aspose AI que se conecta al endpoint predeterminado de Aspose LLM. Este es el cliente usado por el constructor sin parámetros  SlidesAIAgent() , por lo que crearlo explícitamente solo es necesario cuando se pasa el cliente al  SlidesAIAgent(IAIWebClient)  constructor directamente.

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

Crea una instancia del cliente web Aspose AI que se conecta al endpoint predeterminado de Aspose LLM usando un HttpClient gestionado externamente. El HttpClient proporcionado no es eliminado por esta instancia y sigue siendo propiedad del llamador.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpClient gestionada externamente. |
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

Crea una instancia del cliente web Aspose AI que se conecta a una URL de endpoint personalizada. Utilice esta sobrecarga cuando tenga una URL proporcionada por el equipo de Aspose.Slides; de lo contrario, use la sobrecarga  AsposeAIWebClient()  con la URL predeterminada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del endpoint de Aspose LLM, proporcionada por el equipo de Aspose.Slides. |
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

Crea una instancia del cliente web Aspose AI que se conecta a una URL de endpoint personalizada usando un HttpClient gestionado externamente. El HttpClient proporcionado no es eliminado por esta instancia y sigue siendo propiedad del llamador. Utilice esta sobrecarga cuando tenga una URL proporcionada por el equipo de Aspose.Slides y desee suministrar su propio HttpClient; si solo necesita su propio HttpClient con la URL predeterminada, use la sobrecarga  AsposeAIWebClient(HttpClient)  en su lugar.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del endpoint de Aspose LLM, proporcionada por el equipo de Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpClient gestionada externamente. |
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

Envía una instrucción de chat al modelo de IA usando una instancia de HttpConnection proporcionada y devuelve el mensaje de respuesta a la instrucción dada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Devuelve:**
java.lang.String
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