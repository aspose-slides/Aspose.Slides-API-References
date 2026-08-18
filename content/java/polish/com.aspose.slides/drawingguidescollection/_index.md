---
title: DrawingGuidesCollection
second_title: Aspose.Slides dla Java Odniesienie API
description: Reprezentuje kolekcję regulowanych prowadnic rysunkowych.
type: docs
url: /pl/com.aspose.slides/drawingguidescollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Reprezentuje kolekcję regulowanych prowadnic rysunkowych.
## Metody

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca prowadnicę rysunkową według indeksu. |
| [add(byte orientation, float position)](#add-byte-float-) | Dodaje prowadnicę rysunkową na końcu kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa prowadnicę rysunkową o określonym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [getCount()](#getCount--) | Zwraca liczbę elementów w kolekcji. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Zwraca prowadnicę rysunkową według indeksu. Tylko do odczytu [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Dodaje prowadnicę rysunkową na końcu kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientation | byte | Orientacja prowadnicy rysunkowej. |
| position | float | Pozycja prowadnicy rysunkowej w punktach. |

**Zwraca:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa prowadnicę rysunkową o określonym indeksie.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks prowadnicy rysunkowej, która ma zostać usunięta. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie elementy z kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - IGenericEnumerator, który można użyć do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - java.util.Iterator dla całej kolekcji.
### getCount() {#getCount--}
```
public final int getCount()
```


Zwraca liczbę elementów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |