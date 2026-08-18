---
title: CellInvalidReferenceException
second_title: Aspose.Slides Java API Referencia
description: Az a kivétel, amely akkor kerül dobásra, amikor egy érvénytelen cellahivatkozás található.
type: docs
url: /hu/com.aspose.slides/cellinvalidreferenceexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Az a kivétel, amely akkor kerül dobásra, amikor egy érvénytelen cellahivatkozás található.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Új példányt hoz létre a(z) [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályban. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Új példányt hoz létre a(z) [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályban a megadott hibaüzenettel. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Új példányt hoz létre a(z) [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályban a megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az oka. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Új példányt hoz létre a(z) [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályban a megadott hibaüzenettel és egy érvénytelen cellahivatkozással. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getReference()](#getReference--) | Egy érvénytelen cellahivatkozást ad vissza. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Új példányt hoz létre a(z) [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályban.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Új példányt hoz létre a(z) [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályban a megadott hibaüzenettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Új példányt hoz létre a(z) [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályban a megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az oka.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |
| innerException | java.lang.RuntimeException | A kivétel, amely az aktuális kivétel okát jelenti. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Új példányt hoz létre a(z) [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályban a megadott hibaüzenettel és egy érvénytelen cellahivatkozással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |
| reference | java.lang.String | Érvénytelen cellahivatkozás. |

### getReference() {#getReference--}
```
public final String getReference()
```


Egy érvénytelen cellahivatkozást ad vissza.

**Visszatérési érték:**
java.lang.String