---
title: PieSplitCustomPointCollection
second_title: Dokumentacja API Aspose.Slides dla Javy
description: Reprezentuje kolekcję punktów służących do podziału w wykresie słupkowo-pirowym lub wykresie pirowym z niestandardowym podziałem.
type: docs
url: /pl/com.aspose.slides/piesplitcustompointcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Reprezentuje kolekcję punktów służących do podziału w wykresie słupkowo-pirowym lub wykresie pirowym z niestandardowym podziałem.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca punkt danych wykresu dla określonego indeksu. |
| [add(int dataPointIndex)](#add-int-) | Dodaje punkt danych według jego indeksu w kolekcji punktów serii nadrzędnej. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Dodaje punkt danych do kolekcji. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Usuwa element z kolekcji. |
| [remove(int dataPointIndex)](#remove-int-) | Usuwa element z kolekcji według jego indeksu w kolekcji punktów serii nadrzędnej. |
| [clear()](#clear--) | Usuwa wszystkie elementy z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy. |
| [size()](#size--) | Zwraca lub ustawia liczbę punktów danych wykresu. |
| [isReadOnly()](#isReadOnly--) | Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (bezpieczny dla wątków). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca iterator, który przegląda kolekcję. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Javy dla całej kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```


Zwraca punkt danych wykresu dla określonego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks. |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Punkt danych wykresu.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```


Dodaje punkt danych według jego indeksu w kolekcji punktów serii nadrzędnej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPointIndex | int | Indeks punktu danych w kolekcji punktów serii nadrzędnej. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```


Dodaje punkt danych do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Punkt danych, do którego dodaje się element. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```


Usuwa element z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Punkt danych, którego element ma zostać usunięty. |

**Zwraca:**
boolean - true, jeśli element został pomyślnie usunięty; w przeciwnym razie false. Metoda zwraca również false, jeśli element nie został znaleziony w System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```


Usuwa element z kolekcji według jego indeksu w kolekcji punktów serii nadrzędnej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPointIndex | int | Indeks punktu danych w kolekcji punktów serii nadrzędnej. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie elementy z [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```


Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Obiekt, który ma zostać odnaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true, jeśli element zostanie znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```


Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Jednowymiarowa tablica będąca miejscem docelowym elementów kopiowanych z [IGenericCollection](../../com.aspose.slides/igenericcollection). Tablica musi mieć indeksowanie zerobazowe. |
| arrayIndex | int | Zerobazowy indeks w tablicy, od którego rozpoczyna się kopiowanie. |

### size() {#size--}
```
public final int size()
```


Zwraca lub ustawia liczbę punktów danych wykresu. Tylko do odczytu int.

**Zwraca:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. Tylko do odczytu boolean.

**Zwraca:**
boolean - true, jeśli [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu; w przeciwnym razie false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (bezpieczny dla wątków). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```


Zwraca iterator, który przegląda kolekcję.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator, którego można użyć do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


Zwraca iterator Javy dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator dla całej kolekcji.