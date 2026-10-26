---
title: PptxException
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Představuje standardní interní typ výjimky.
type: docs
url: /cs/com.aspose.slides/pptxexception/
---
**Dědění:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

Představuje standardní interní typ výjimky.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PptxException()](#PptxException--) | Výchozí konstruktor. |
| [PptxException(String message)](#PptxException-java.lang.String-) | Konstruktor umožňující přidat zprávu k této výjimce. |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | Konstruktor pro výjimku obsahující zprávu a vloženou výjimku. |
### PptxException() {#PptxException--}
```
public PptxException()
```


Výchozí konstruktor.

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```


Konstruktor umožňující přidat zprávu k této výjimce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | zpráva |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```


Konstruktor pro výjimku obsahující zprávu a vloženou výjimku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | zpráva |
| exception | java.lang.RuntimeException | původní výjimka |