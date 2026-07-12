---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
type: docs
url: /es/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Representa una instancia de conversación. A diferencia de las llamadas regulares de IA, las conversaciones conservan todo el contexto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Envía un mensaje de solicitud de conversación que incluye todo el contexto y devuelve la respuesta. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Envía un mensaje de solicitud de conversación que incluye todo el contexto y devuelve la respuesta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| instruction | java.lang.String | La instrucción o mensaje que será procesado por el modelo de IA. |

**Devuelve:**
java.lang.String - El mensaje generado por el modelo de IA en respuesta a la instrucción dada dentro del contexto de la conversación.