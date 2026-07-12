---
title: CellInvalidFormulaException
second_title: Aspose.Slides Androidhoz Java API Referencia
description: A kivétel, amely akkor dobódik, ha egy kiszámított képlet helytelen vagy nem lett értelmezve.
type: docs
url: /hu/com.aspose.slides/cellinvalidformulaexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

A kivétel akkor dobódik, ha egy kiszámított képlet helytelen vagy nem lett értelmezve.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból a megadott hibaüzenettel. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból a megadott hibaüzenettel és egy belső kivétel hivatkozással, amely ennek a kivételnek az okát jelenti. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból a megadott hibaüzenettel és egy cellahivatkozással, amely a hibás képletet tartalmazza. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getReference()](#getReference--) | Cellahivatkozást ad vissza, amely a hibás képletet tartalmazza. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```


Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```


Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból a megadott hibaüzenettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```


Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból a megadott hibaüzenettel és egy belső kivétel hivatkozással, amely az aktuális kivétel okát jelenti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |
| innerException | java.lang.RuntimeException | Az a kivétel, amely a jelenlegi kivétel okát jelenti. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```


Új példányt inicializál a(z) [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból a megadott hibaüzenettel és egy cellahivatkozással, amely a hibás képletet tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |
| reference | java.lang.String | A belső kivételre mutató hivatkozást leíró karakterlánc. |

### getReference() {#getReference--}
```
public final String getReference()
```


Cellahivatkozást ad vissza, amely a hibás képletet tartalmazza.

**Visszatérési érték:**
java.lang.String