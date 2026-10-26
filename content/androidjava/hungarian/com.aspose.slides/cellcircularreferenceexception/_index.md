---
title: CellCircularReferenceException
second_title: Aspose.Slides Androidra vonatkozó Java API-referencia
description: Az a kivétel, amely akkor kerül dobásra, amikor egy vagy több körkörös hivatkozás van észlelve, és egy képlet közvetlenül vagy közvetve a saját cellájára hivatkozik.
type: docs
url: /hu/com.aspose.slides/cellcircularreferenceexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Az a kivétel, amely akkor kerül dobásra, amikor egy vagy több körkörös hivatkozás van észlelve, és egy képlet közvetlenül vagy közvetve a saját cellájára hivatkozik.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and circular cell reference. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getReference()](#getReference--) | Lekéri a körkörös cellahivatkozást. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Új példányt hoz létre a(z) [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztály.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Új példányt hoz létre a(z) [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályban megadott hibaüzenettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Új példányt hoz létre a(z) [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályban megadott hibaüzenettel és a belső kivételre mutató hivatkozással, amely ennek a kivételnek az okát jelenti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |
| innerException | java.lang.RuntimeException | A kivétel, amely az aktuális kivétel okát képezi. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Új példányt hoz létre a(z) [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályban megadott hibaüzenettel és körkörös cellahivatkozással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |
| reference | java.lang.String | Egy körkörös cellahivatkozás. |

### getReference() {#getReference--}
```
public final String getReference()
```

Lekéri a körkörös cellahivatkozást.

**Visszatérési érték:**
java.lang.String