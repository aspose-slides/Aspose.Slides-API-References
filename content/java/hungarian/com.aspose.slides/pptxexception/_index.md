---
title: PptxException
second_title: Aspose.Slides Java API referencia
description: Egy szabványos belső kivétel típusát képviseli.
type: docs
url: /hu/com.aspose.slides/pptxexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

Egy szabványos belső kivétel típusát képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptxException()](#PptxException--) | Alapértelmezett konstruktor. |
| [PptxException(String message)](#PptxException-java.lang.String-) | Konstruktor, amely lehetővé teszi egy üzenet hozzáadását ehhez a kivételhez. |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | Konstruktor egy olyan kivételhez, amely üzenetet és beágyazott kivételt tartalmaz. |
### PptxException() {#PptxException--}
```
public PptxException()
```

Alapértelmezett konstruktor.

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```

Konstruktor, amely lehetővé teszi egy üzenet hozzáadását ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```

Konstruktor egy olyan kivételhez, amely üzenetet és beágyazott kivételt tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |