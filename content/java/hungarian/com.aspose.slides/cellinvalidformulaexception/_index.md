---
title: CellInvalidFormulaException
second_title: Aspose.Slides Java API referencia
description: Az a kivétel, amely akkor kerül dobásra, amikor egy kiszámított képlet nem helyes vagy nem lett értelmezve.
type: docs
url: /hu/com.aspose.slides/cellinvalidformulaexception/
---
**Öröklés:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Az a kivétel, amely akkor kerül dobásra, amikor egy kiszámított képlet nem helyes vagy nem lett értelmezve.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból egy megadott hibaüzenettel. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból egy megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az oka. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból egy megadott hibaüzenettel és egy cellahivatkozással, amely az érvénytelen képletet tartalmazza. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getReference()](#getReference--) | Lekér egy cellahivatkozást, amely az érvénytelen képletet tartalmazza. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból egy megadott hibaüzenettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |
### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból egy megadott hibaüzenettel és egy hivatkozással a belső kivételre, amely ennek a kivételnek az oka.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |
| innerException | java.lang.RuntimeException | A jelenlegi kivétel okát jelentő kivétel. |
### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Inicializál egy új példányt a [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) osztályból egy megadott hibaüzenettel és egy cellahivatkozással, amely az érvénytelen képletet tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| message | java.lang.String | A hibát leíró karakterlánc. |
| reference | java.lang.String | A belső kivételre mutató hivatkozást leíró karakterlánc. |
### getReference() {#getReference--}
```
public final String getReference()
```

Lekér egy cellahivatkozást, amely az érvénytelen képletet tartalmazza.

**Visszatérési érték:**
java.lang.String