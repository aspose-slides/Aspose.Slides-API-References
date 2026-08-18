---
title: PptEditException
second_title: Aspose.Slides Java API referencia
description: Olyan kivételt képvisel, amely akkor kerül dobásra, amikor szerkesztési prezentációs hiba észlelhető.
type: docs
url: /hu/com.aspose.slides/ppteditexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.PptException](../../com.aspose.slides/pptexception)
```
public class PptEditException extends PptException
```

A kivétel, amely akkor kerül dobásra, amikor szerkesztési prezentációs hiba észlelhető.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptEditException()](#PptEditException--) | Alapértelmezett konstruktor. |
| [PptEditException(String message)](#PptEditException-java.lang.String-) | Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez. |
| [PptEditException(String message, RuntimeException exception)](#PptEditException-java.lang.String-java.lang.RuntimeException-) | Konstruktor, amely üzenetet és beágyazott kivételt tartalmazó kivételt hoz létre. |
### PptEditException() {#PptEditException--}
```
public PptEditException()
```


Alapértelmezett konstruktor.

### PptEditException(String message) {#PptEditException-java.lang.String-}
```
public PptEditException(String message)
```


Konstruktor, amely lehetővé teszi üzenet hozzáadását ehhez a kivételhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |

### PptEditException(String message, RuntimeException exception) {#PptEditException-java.lang.String-java.lang.RuntimeException-}
```
public PptEditException(String message, RuntimeException exception)
```


Konstruktor, amely üzenetet és beágyazott kivételt tartalmazó kivételt hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | üzenet |
| exception | java.lang.RuntimeException | eredeti kivétel |