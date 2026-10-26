---
title: ColorOperation
second_title: Aspose.Slides dla Androida – Java API Reference
description: Reprezentuje różne operacje kolorów używane do przekształceń kolorów.
type: docs
url: /pl/com.aspose.slides/coloroperation/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Reprezentuje różne operacje kolorów używane do przekształceń kolorów. Obiekt niezmienny.
## Constructors

| Konstruktor | Opis |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Tworzy nową operację przekształcenia koloru. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Tworzy nową operację przekształcenia koloru. |
## Methods

| Metoda | Opis |
| --- | --- |
| [getOperationType()](#getOperationType--) | Zwraca lub ustawia typ operacji. |
| [getParameter()](#getParameter--) | Zwraca parametr operacji. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy dwa obiekty ColorOperation są równe. |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszowania i strukturach danych, takich jak tablica mieszająca. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Tworzy nową operację przekształcenia koloru.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| op | int | Typ operacji. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Tworzy nową operację przekształcenia koloru.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| op | int | Typ operacji. |
| parameter | float | Parametr operacji. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Zwraca lub ustawia typ operacji. Tylko do odczytu [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Zwraca:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Zwraca parametr operacji. Tylko do odczytu float.

**Zwraca:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy dwa obiekty ColorOperation są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt ColorOperation do porównania z bieżącym ColorOperation. |

**Zwraca:**
boolean - **true**, jeśli określony ColorOperation jest równy bieżącemu ColorOperation; w przeciwnym razie **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszowania i strukturach danych, takich jak tablica mieszająca.

**Zwraca:**
int