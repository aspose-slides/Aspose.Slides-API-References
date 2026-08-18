---
title: CellCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kolekcję komórek.
type: docs
url: /pl/com.aspose.slides/cellcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Reprezentuje kolekcję komórek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Zwraca liczbę komórek w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca komórkę według jej pozycji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny kolekcji CellCollection. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną kolekcji CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


Zwraca liczbę komórek w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


Zwraca komórkę według jej pozycji. Tylko do odczytu [Cell](../../com.aspose.slides/cell).

--------------------

Jeden obiekt Cell może być zwrócony dla kilku indeksów w przypadku, gdy komórka jest scalona.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - IGenericEnumerator, który może być używany do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - java.util.Iterator dla całej kolekcji.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Zwraca slajd nadrzędny kolekcji CellCollection. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Zwraca prezentację nadrzędną kolekcji CellCollection. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object