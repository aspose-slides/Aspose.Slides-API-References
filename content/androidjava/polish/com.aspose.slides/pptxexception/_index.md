---
title: PptxException
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje standardowy wewnętrzny typ wyjątku.
type: docs
url: /pl/com.aspose.slides/pptxexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

Reprezentuje standardowy wewnętrzny typ wyjątku.
## Constructors

| Constructor | Description |
| --- | --- |
| [PptxException()](#PptxException--) | Domyślny konstruktor. |
| [PptxException(String message)](#PptxException-java.lang.String-) | Konstruktor pozwalający dodać komunikat do tego wyjątku. |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | Konstruktor wyjątku zawierającego komunikat i wbudowany wyjątek. |
### PptxException() {#PptxException--}
```
public PptxException()
```


Domyślny konstruktor.

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```


Konstruktor pozwalający dodać komunikat do tego wyjątku.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | komunikat |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```


Konstruktor wyjątku zawierającego komunikat i wbudowany wyjątek.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | komunikat |
| exception | java.lang.RuntimeException | oryginalny wyjątek |