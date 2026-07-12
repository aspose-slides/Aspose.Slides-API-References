---
title: PptxException
second_title: Referencia de API de Java de Aspose.Slides para Android
description: Representa un tipo de excepción interno estándar.
type: docs
url: /es/com.aspose.slides/pptxexception/
---
**Herencia:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

Representa un tipo de excepción interno estándar.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PptxException()](#PptxException--) | Constructor predeterminado. |
| [PptxException(String message)](#PptxException-java.lang.String-) | Constructor que permite agregar un mensaje a esta excepción. |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | Constructor para una excepción que contiene un mensaje y una excepción incrustada. |
### PptxException() {#PptxException--}
```
public PptxException()
```

Constructor predeterminado.

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```

Constructor que permite agregar un mensaje a esta excepción.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | message |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```

Constructor para una excepción que contiene un mensaje y una excepción incrustada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |