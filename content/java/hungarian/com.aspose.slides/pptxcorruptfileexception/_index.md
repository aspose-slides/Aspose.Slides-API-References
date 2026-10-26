---
title: PptxCorruptFileException
second_title: Aspose.Slides Java API Referencia
description: Kivétel, amely akkor dobódik, amikor a prezentációfájl valószínűleg sérült.
type: docs
url: /hu/com.aspose.slides/pptxcorruptfileexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxReadException](../../com.aspose.slides/pptxreadexception)
```
public class PptxCorruptFileException extends PptxReadException
```

Kivétel, amely akkor dobódik, amikor a prezentációfájl valószínűleg sérült.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptxCorruptFileException()](#PptxCorruptFileException--) | Alapértelmezett konstruktor. |
| [PptxCorruptFileException(String message)](#PptxCorruptFileException-java.lang.String-) | Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez. |
| [PptxCorruptFileException(String message, RuntimeException exception)](#PptxCorruptFileException-java.lang.String-java.lang.RuntimeException-) | Konstruktor egy olyan kivételhez, amely üzenetet és egy beágyazott kivételt tartalmaz. |
### PptxCorruptFileException() {#PptxCorruptFileException--}
```
public PptxCorruptFileException()
```


Alapértelmezett konstruktor.

### PptxCorruptFileException(String message) {#PptxCorruptFileException-java.lang.String-}
```
public PptxCorruptFileException(String message)
```


Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### PptxCorruptFileException(String message, RuntimeException exception) {#PptxCorruptFileException-java.lang.String-java.lang.RuntimeException-}
```
public PptxCorruptFileException(String message, RuntimeException exception)
```


Konstruktor egy olyan kivételhez, amely üzenetet és egy beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |