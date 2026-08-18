---
title: PptxReadException
second_title: Aspose.Slides Java API hivatkozás
description: Olyan kivételt reprezentál, amely a prezentáció olvasási hibái során kerül dobásra.
type: docs
url: /hu/com.aspose.slides/pptxreadexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception)
```
public class PptxReadException extends PptxException
```

Represents an exception which thrown on presentation reading errors.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptxReadException()](#PptxReadException--) | Alapértelmezett konstruktor. |
| [PptxReadException(String message)](#PptxReadException-java.lang.String-) | Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez. |
| [PptxReadException(String message, RuntimeException exception)](#PptxReadException-java.lang.String-java.lang.RuntimeException-) | Konstruktor egy olyan kivételhez, amely üzenetet és egy beágyazott kivételt tartalmaz. |
### PptxReadException() {#PptxReadException--}
```
public PptxReadException()
```


Alapértelmezett konstruktor.

### PptxReadException(String message) {#PptxReadException-java.lang.String-}
```
public PptxReadException(String message)
```


Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### PptxReadException(String message, RuntimeException exception) {#PptxReadException-java.lang.String-java.lang.RuntimeException-}
```
public PptxReadException(String message, RuntimeException exception)
```


Konstruktor egy olyan kivételhez, amely üzenetet és egy beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |