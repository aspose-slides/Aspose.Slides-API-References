---
title: PptxException
second_title: Aspose.Slides dla Java – Odniesienie API
description: Reprezentuje standardowy wewnętrzny typ wyjątku.
type: docs
url: /pl/com.aspose.slides/pptxexception/
---
**Dziedziczenie:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

Reprezentuje standardowy wewnętrzny typ wyjątku.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PptxException()](#PptxException--) | Domyślny konstruktor. |
| [PptxException(String message)](#PptxException-java.lang.String-) | Konstruktor umożliwiający dodanie komunikatu do tego wyjątku. |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | Konstruktor dla wyjątku zawierającego komunikat i wbudowany wyjątek. |
### PptxException() {#PptxException--}
```
public PptxException()
```


Domyślny konstruktor.

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```


Konstruktor umożliwiający dodanie komunikatu do tego wyjątku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | message |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```


Konstruktor dla wyjątku zawierającego komunikat i wbudowany wyjątek.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |