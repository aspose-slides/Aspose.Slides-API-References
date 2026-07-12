---
title: PptxReadException
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Olyan kivételt reprezentál, amely a prezentáció olvasási hibái esetén keletkezik.
type: docs
url: /hu/com.aspose.slides/pptxreadexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception)
```
public class PptxReadException extends PptxException
```

A bemutató olvasási hibái során keletkezett kivételt reprezentálja.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptxReadException()](#PptxReadException--) | Default constructor. |
| [PptxReadException(String message)](#PptxReadException-java.lang.String-) | Constructor allowing a message to be added to this exception. |
| [PptxReadException(String message, RuntimeException exception)](#PptxReadException-java.lang.String-java.lang.RuntimeException-) | Constructor for an exception containing a message and an embedded exception. |
### PptxReadException() {#PptxReadException--}
```
public PptxReadException()
```

Alapértelmezett konstruktor.

### PptxReadException(String message) {#PptxReadException-java.lang.String-}
```
public PptxReadException(String message)
```

Konstruktor, amely üzenetet adhat a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | message |

### PptxReadException(String message, RuntimeException exception) {#PptxReadException-java.lang.String-java.lang.RuntimeException-}
```
public PptxReadException(String message, RuntimeException exception)
```

Konstruktor egy olyan kivételhez, amely tartalmaz üzenetet és egy beágyazott kivételt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | eredeti kivétel |