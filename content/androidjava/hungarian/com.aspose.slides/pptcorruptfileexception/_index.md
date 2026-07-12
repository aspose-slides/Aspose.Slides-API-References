---
title: PptCorruptFileException
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Kivétel, amely akkor kerül dobásra, ha a prezentáció fájl valószínűleg sérült.
type: docs
url: /hu/com.aspose.slides/pptcorruptfileexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.PptException](../../com.aspose.slides/pptexception), [com.aspose.slides.PptReadException](../../com.aspose.slides/pptreadexception)
```
public class PptCorruptFileException extends PptReadException
```

Kivétel, amely akkor kerül dobásra, amikor a prezentáció fájl valószínűleg sérült.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptCorruptFileException()](#PptCorruptFileException--) | Alapértelmezett konstruktor. |
| [PptCorruptFileException(String message)](#PptCorruptFileException-java.lang.String-) | Konstruktor, amely lehetővé teszi, hogy üzenetet adjon hozzá ehhez a kivételhez. |
| [PptCorruptFileException(String message, RuntimeException exception)](#PptCorruptFileException-java.lang.String-java.lang.RuntimeException-) | Konstruktor egy olyan kivételhez, amely tartalmaz üzenetet és egy beágyazott kivételt. |
### PptCorruptFileException() {#PptCorruptFileException--}
```
public PptCorruptFileException()
```


Alapértelmezett konstruktor.

### PptCorruptFileException(String message) {#PptCorruptFileException-java.lang.String-}
```
public PptCorruptFileException(String message)
```


Konstruktor, amely lehetővé teszi, hogy üzenetet adjon hozzá ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | message |

### PptCorruptFileException(String message, RuntimeException exception) {#PptCorruptFileException-java.lang.String-java.lang.RuntimeException-}
```
public PptCorruptFileException(String message, RuntimeException exception)
```


Konstruktor egy olyan kivételhez, amely tartalmaz üzenetet és egy beágyazott kivételt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |