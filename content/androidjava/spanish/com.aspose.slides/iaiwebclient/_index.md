---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web client interface.
type: docs
url: /es/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interfaz de cliente AI Web. Esta interfaz permite sustituir diferentes modelos de lenguaje AI. Las clases que implementan esta interfaz deben usarse junto con SlidesAIAgent.
## Métodos

| Método | Descripción |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envía una instrucción de chat al modelo AI utilizando una instancia proporcionada de HttpConnection y devuelve el mensaje de respuesta a la instrucción dada. |
| [createConversation()](#createConversation--) | Crea una instancia de conversación. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


Envía una instrucción de chat al modelo AI utilizando una instancia proporcionada de HttpConnection y devuelve el mensaje de respuesta a la instrucción dada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instruction | java.lang.String | La instrucción o mensaje que será procesado por el modelo AI. |

**Devuelve:**
java.lang.String - El mensaje generado por el modelo AI en respuesta a la instrucción dada.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```


Crea una instancia de conversación. A diferencia de las llamadas AI regulares, las conversaciones conservan todo el contexto.

**Devuelve:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Una instancia de [IAIConversation](../../com.aspose.slides/iaiconversation).