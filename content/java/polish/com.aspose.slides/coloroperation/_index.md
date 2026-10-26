---
title: ColorOperation
second_title: Aspose.Slides dla Java API Reference
description: Reprezentuje różne operacje kolorów używane do transformacji kolorów.
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

Reprezentuje różne operacje kolorów używane do transformacji kolorów. Obiekt niemutowalny.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Tworzy nową operację transformacji koloru. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Tworzy nową operację transformacji koloru. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getOperationType()](#getOperationType--) | Zwraca lub ustawia typ operacji. |
| [getParameter()](#getParameter--) | Zwraca parametr operacji. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy dwie instancje ColorOperation są równe. |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszujących i strukturach danych takich jak tablica skrótu. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Tworzy nową operację transformacji koloru.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| op | int | Typ operacji. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Tworzy nową operację transformacji koloru.

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


Określa, czy dwie instancje ColorOperation są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation, z którym porównywany jest bieżący ColorOperation. |

**Zwraca:**
boolean - **true** jeśli podany ColorOperation jest równy bieżącemu ColorOperation; w przeciwnym razie **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszujących i strukturach danych takich jak tablica skrótu.

**Zwraca:**
int