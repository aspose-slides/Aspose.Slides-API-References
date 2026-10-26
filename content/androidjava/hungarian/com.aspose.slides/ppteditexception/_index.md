---
title: PptEditException
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Kivételt ábrázol, amelyet a bemutató szerkesztési hibájának észlelésekor dobnak.
type: docs
url: /hu/com.aspose.slides/ppteditexception/
---
**Öröklődés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.PptException](../../com.aspose.slides/pptexception)
```
public class PptEditException extends PptException
```

Egy olyan kivételt ábrázol, amelyet a bemutató szerkesztési hibájának észlelésekor dobnak.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptEditException()](#PptEditException--) | Alapértelmezett konstruktor. |
| [PptEditException(String message)](#PptEditException-java.lang.String-) | Konstruktor, amely lehetővé teszi, hogy üzenetet adjon ehhez a kivételhez. |
| [PptEditException(String message, RuntimeException exception)](#PptEditException-java.lang.String-java.lang.RuntimeException-) | Konstruktor egy olyan kivételhez, amely üzenetet és beágyazott kivételt tartalmaz. |
### PptEditException() {#PptEditException--}
```
public PptEditException()
```

Alapértelmezett konstruktor.

### PptEditException(String message) {#PptEditException-java.lang.String-}
```
public PptEditException(String message)
```

Konstruktor, amely lehetővé teszi, hogy üzenetet adjon ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | message |

### PptEditException(String message, RuntimeException exception) {#PptEditException-java.lang.String-java.lang.RuntimeException-}
```
public PptEditException(String message, RuntimeException exception)
```

Konstruktor egy olyan kivételhez, amely üzenetet és beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |