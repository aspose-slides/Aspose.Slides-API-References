---
title: CellCircularReferenceException
second_title: Aspose.Slides Java API hivatkozás
description: Az a kivétel, amely akkor kerül dobásra, amikor egy vagy több körkörös hivatkozás kerül észlelésre, ahol egy képlet közvetlenül vagy közvetve a saját cellájára hivatkozik.
type: docs
url: /hu/com.aspose.slides/cellcircularreferenceexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Az a kivétel, amely akkor kerül dobásra, amikor egy vagy több körkörös hivatkozás kerül észlelésre, ahol egy képlet közvetlenül vagy közvetve a saját cellájára hivatkozik.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból megadott hibaüzenettel. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az okát képezi. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból megadott hibaüzenettel és körkörös cellahivatkozással. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getReference()](#getReference--) | Lekéri egy körkörös cellahivatkozást. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból megadott hibaüzenettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az okát képezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |
| innerException | java.lang.RuntimeException | A kivétel, amely a jelenlegi kivétel okát képezi. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Inicializál egy új példányt a [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) osztályból megadott hibaüzenettel és körkörös cellahivatkozással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | Egy karakterlánc, amely leírja a hibát. |
| reference | java.lang.String | Egy körkörös cellahivatkozás. |

### getReference() {#getReference--}
```
public final String getReference()
```

Lekéri egy körkörös cellahivatkozást.

**Visszatér:**
java.lang.String