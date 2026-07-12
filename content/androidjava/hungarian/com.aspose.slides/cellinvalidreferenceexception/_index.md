---
title: CellInvalidReferenceException
second_title: Aspose.Slides Androidhoz a Java API referenciája
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
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Inicializál egy új példányt a [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályból. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Inicializál egy új példányt a [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályból egy megadott hibaüzenettel. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializál egy új példányt a [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályból egy megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az okát képezi. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból egy megadott hibaüzenettel és egy érvénytelen cellahivatkozással. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getReference()](#getReference--) | Lekér egy érvénytelen cellahivatkozást. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Inicializál egy új példányt a [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályból.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Inicializál egy új példányt a [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályból egy megadott hibaüzenettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Inicializál egy új példányt a [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) osztályból egy megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az okát képezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |
| innerException | java.lang.RuntimeException | A kivétel, amely az aktuális kivétel okát jelenti. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból egy megadott hibaüzenettel és egy érvénytelen cellahivatkozással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |
| reference | java.lang.String | Egy érvénytelen cellahivatkozás. |

### getReference() {#getReference--}
```
public final String getReference()
```

Lekér egy érvénytelen cellahivatkozást.

**Visszatérési érték:**
java.lang.String