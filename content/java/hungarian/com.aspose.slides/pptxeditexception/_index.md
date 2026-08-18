---
title: PptxEditException
second_title: Aspose.Slides Java API referencia
description: Olyan kivételt jelöl, amely akkor kerül dobásra, amikor a prezentáció szerkesztésének hibája észlelésre kerül.
type: docs
url: /hu/com.aspose.slides/pptxeditexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception)
```
public class PptxEditException extends PptxException
```

Olyan kivételt jelöl, amely akkor kerül dobásra, amikor a prezentáció szerkesztésének hibája észlelésre kerül.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptxEditException()](#PptxEditException--) | Alapértelmezett konstruktor. |
| [PptxEditException(String message)](#PptxEditException-java.lang.String-) | Konstruktor, amely lehetővé teszi, hogy üzenetet adjunk ehhez a kivételhez. |
| [PptxEditException(String message, RuntimeException exception)](#PptxEditException-java.lang.String-java.lang.RuntimeException-) | Konstruktor, amely olyan kivételt hoz létre, amely üzenetet és beágyazott kivételt tartalmaz. |
### PptxEditException() {#PptxEditException--}
```
public PptxEditException()
```


Alapértelmezett konstruktor.

### PptxEditException(String message) {#PptxEditException-java.lang.String-}
```
public PptxEditException(String message)
```


Konstruktor, amely lehetővé teszi, hogy üzenetet adjunk ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### PptxEditException(String message, RuntimeException exception) {#PptxEditException-java.lang.String-java.lang.RuntimeException-}
```
public PptxEditException(String message, RuntimeException exception)
```


Konstruktor, amely olyan kivételt hoz létre, amely üzenetet és beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |