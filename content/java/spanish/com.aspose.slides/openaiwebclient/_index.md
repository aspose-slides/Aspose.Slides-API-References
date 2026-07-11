---
title: OpenAIWebClient
second_title: Referencia de API de Aspose.Slides para Java
description: Una implementación incorporada que se conecta a la API de OpenAI.
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

Una implementación incorporada [IAIWebClient](../../com.aspose.slides/iaiwebclient) que se conecta a la API de OpenAI.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crea una instancia del cliente web de OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crea una instancia del cliente web de OpenAI que utiliza un HttpClient gestionado externamente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crea una instancia de conversación. |
| [close()](#close--) | Libera los recursos utilizados por esta instancia. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Crea una instancia del cliente web de OpenAI.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Modelo de lenguaje OpenAI. Valores posibles: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clave API de OpenAI. |
| organizationId | java.lang.String | ID de organización (opcional). |

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

Crea una instancia del cliente web de OpenAI que utiliza un HttpClient gestionado externamente. El HttpClient proporcionado no es eliminado por esta instancia y sigue siendo propiedad del llamador.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Modelo de lenguaje OpenAI. Valores posibles: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clave API de OpenAI |
| organizationId | java.lang.String | ID de organización (opcional) |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpClient gestionada externamente |

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

Envía una instrucción de chat al modelo de IA usando una instancia HttpConnection proporcionada y devuelve el mensaje de respuesta a la instrucción dada.

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

Crea una instancia de conversación. A diferencia de las llamadas regulares a IA, las conversaciones conservan todo el contexto.

**Devuelve:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una instancia de [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Libera los recursos utilizados por esta instancia.