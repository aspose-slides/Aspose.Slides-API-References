---
title: CellInvalidReferenceException
second_title: Aspose.Slides dla Androida przy użyciu interfejsu API Java
description: Wyjątek zgłaszany, gdy napotkano nieprawidłowe odwołanie do komórki.
type: docs
url: /pl/com.aspose.slides/cellinvalidreferenceexception/
---
**Dziedziczenie:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Wyjątek, który jest zgłaszany, gdy napotkano nieprawidłowe odwołanie do komórki.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Inicjalizuje nową instancję klasy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Inicjalizuje nową instancję klasy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) z określonym komunikatem o błędzie. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicjalizuje nową instancję klasy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) z określonym komunikatem o błędzie oraz odwołaniem do wewnętrznego wyjątku będącego przyczyną tego wyjątku. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie i nieprawidłowym odwołaniem do komórki. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getReference()](#getReference--) | Pobiera nieprawidłowe odwołanie do komórki. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Inicjalizuje nową instancję klasy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Inicjalizuje nową instancję klasy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) z określonym komunikatem o błędzie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Inicjalizuje nową instancję klasy [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) z określonym komunikatem o błędzie oraz odwołaniem do wewnętrznego wyjątku będącego przyczyną tego wyjątku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |
| innerException | java.lang.RuntimeException | Wyjątek będący przyczyną bieżącego wyjątku. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie i nieprawidłowym odwołaniem do komórki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |
| reference | java.lang.String | Nieprawidłowe odwołanie do komórki. |

### getReference() {#getReference--}
```
public final String getReference()
```

Pobiera nieprawidłowe odwołanie do komórki.

**Zwraca:**
java.lang.String