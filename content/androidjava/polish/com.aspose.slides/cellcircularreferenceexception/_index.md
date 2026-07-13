---
title: CellCircularReferenceException
second_title: Aspose.Slides dla Androida przez interfejs API Java
description: Wyjątek, który jest zgłaszany, gdy wykryto jedną lub więcej referencji cyklicznych, w których formuła odnosi się do własnej komórki bezpośrednio lub pośrednio.
type: docs
url: /pl/com.aspose.slides/cellcircularreferenceexception/
---
**Dziedziczenie:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Wyjątek, który jest wyrzucany, gdy wykryto jedną lub więcej referencji cyklicznych, w których formuła odwołuje się do własnej komórki bezpośrednio lub pośrednio.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie oraz odwołaniem do wewnętrznego wyjątku, będącego przyczyną tego wyjątku. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie i referencją do komórki cyklicznej. |

## Metody

| Metoda | Opis |
| --- | --- |
| [getReference()](#getReference--) | Zwraca odwołanie do komórki cyklicznej. |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie oraz odwołaniem do wewnętrznego wyjątku, będącego przyczyną tego wyjątku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |
| innerException | java.lang.RuntimeException | Wyjątek będący przyczyną bieżącego wyjątku. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Inicjalizuje nową instancję klasy [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) z określonym komunikatem o błędzie i referencją do komórki cyklicznej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | Ciąg znaków opisujący błąd. |
| reference | java.lang.String | Referencja do komórki cyklicznej. |

### getReference() {#getReference--}
```
public final String getReference()
```

Zwraca odwołanie do komórki cyklicznej.

**Zwraca:**
java.lang.String