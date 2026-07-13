---
title: PointCollection
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Reprezentuje kolekcję punktów animacji.
type: docs
url: /pl/com.aspose.slides/pointcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Reprezentuje kolekcję punktów animacji.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę punktów w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca punkt o określonym indeksie. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

Zwraca liczbę punktów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

Zwraca punkt o określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[IPoint](../../com.aspose.slides/ipoint) - Obiekt [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Enumerator IGenericEnumerator, który może być używany do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Iterator java.util.Iterator dla całej kolekcji.