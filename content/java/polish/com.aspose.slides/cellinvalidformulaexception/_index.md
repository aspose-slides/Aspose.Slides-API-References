---
title: CellInvalidFormulaException
second_title: Dokumentacja API Aspose.Slides dla Javy
description: Wyjątek rzucany, gdy obliczona formuła jest niepoprawna lub nie została sparsowana.
type: docs
url: /pl/com.aspose.slides/cellinvalidformulaexception/
---
**Dziedziczenie:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Wyjątek rzucany, gdy obliczona formuła jest niepoprawna lub nie została sparsowana.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) z określonym komunikatem błędu. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) z określonym komunikatem błędu oraz referencją do wewnętrznego wyjątku, który jest przyczyną tego wyjątku. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) z określonym komunikatem błędu oraz referencją do komórki zawierającej nieprawidłową formułę. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getReference()](#getReference--) | Pobiera referencję do komórki zawierającej nieprawidłową formułę. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) z określonym komunikatem błędu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) z określonym komunikatem błędu oraz referencją do wewnętrznego wyjątku, który jest przyczyną tego wyjątku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |
| innerException | java.lang.RuntimeException | Wyjątek będący przyczyną bieżącego wyjątku. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Inicjalizuje nową instancję klasy [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) z określonym komunikatem błędu oraz referencją do komórki zawierającej nieprawidłową formułę.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |
| reference | java.lang.String | Ciąg znaków opisujący referencję do wewnętrznego wyjątku |

### getReference() {#getReference--}
```
public final String getReference()
```

Pobiera referencję do komórki zawierającej nieprawidłową formułę.

**Zwraca:**
java.lang.String