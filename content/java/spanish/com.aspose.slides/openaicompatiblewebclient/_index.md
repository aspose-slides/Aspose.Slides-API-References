---
title: OpenAICompatibleWebClient
second_title: Referencia de la API de Aspose.Slides para Java
description: Una implementación integrada que se conecta a un proveedor LLM compatible con OpenAI en una URL base especificada.
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

Una implementación integrada [IAIWebClient](../../com.aspose.slides/iaiwebclient) que se conecta a un proveedor LLM compatible con OpenAI en una URL base especificada.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crea una instancia del cliente web compatible con OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crea una instancia del cliente web compatible con OpenAI que utiliza un HttpClient gestionado externamente. |

## Métodos

| Método | Descripción |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crea una instancia de conversación. |
| [dispose()](#dispose--) | Libera los recursos usados por esta instancia. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Crea una instancia del cliente web compatible con OpenAI.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Nombre del modelo soportado por el proveedor LLM. |
| apiKey | java.lang.String | clave API (token). |
| baseUrl | java.lang.String | URL base del LLM compatible con OpenAI. |
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

Crea una instancia del cliente web compatible con OpenAI que utiliza un HttpClient gestionado externamente. El HttpClient proporcionado no es eliminado por esta instancia y permanece bajo la responsabilidad del llamador.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| model | java.lang.String | Nombre del modelo soportado por el proveedor LLM. |
| apiKey | java.lang.String | clave API (token). |
| baseUrl | java.lang.String | URL base del LLM compatible con OpenAI. |
| httpClient | java.net.HttpURLConnection | Una instancia de HttpClient gestionada externamente. |
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

Envía una instrucción de chat al modelo AI usando una instancia HttpConnection proporcionada y devuelve el mensaje de respuesta a la instrucción dada.

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

Crea una instancia de conversación. A diferencia de las llamadas AI regulares, las conversaciones conservan todo el contexto.

**Devuelve:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una [IAIConversation](../../com.aspose.slides/iaiconversation) instancia.

### dispose() {#dispose--}
```
public final void dispose()
```

Libera los recursos usados por esta instancia.