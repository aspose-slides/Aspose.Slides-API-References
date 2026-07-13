---
title: ChartSeriesCollection
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Reprezentuje kolekcję
type: docs
url: /pl/com.aspose.slides/chartseriescollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Represents collection of [ChartSeries](../../com.aspose.slides/chartseries)
## Metody

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [size()](#size--) | Zwraca liczbę obiektów w kolekcji. |
| [add(int type)](#add-int-) | Tworzy nową serię wykresu i dodaje ją do kolekcji. |
| [insert(int index, int type)](#insert-int-int-) | Tworzy nową serię wykresu i wstawia ją do kolekcji. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Tworzy nową serię wykresu z [ChartDataCell](../../com.aspose.slides/chartdatacell) i dodaje ją do kolekcji. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Tworzy nową serię wykresu z [ChartCellCollection](../../com.aspose.slides/chartcellcollection) i dodaje ją do kolekcji. |
| [add(String name, int type)](#add-java.lang.String-int-) | Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Wyszukuje określony [ChartSeries](../../com.aspose.slides/chartseries) i zwraca indeks zerowy pierwszego wystąpienia w całej Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Usuwa podaną wartość. |
| [removeAt(int index)](#removeAt-int-) | Usuwa kontrolkę ActiveX przechowywaną na określonej pozycji z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie kontrolki z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje całą kolekcję do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


Pobiera element pod określonym indeksem.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Element pod określonym indeksem.
### size() {#size--}
```
public final int size()
```


Zwraca liczbę obiektów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```


Tworzy nową serię wykresu i dodaje ją do kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Typ serii |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nowa seria wykresu.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```


Tworzy nową serię wykresu i wstawia ją do kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


Tworzy nową serię wykresu z [ChartDataCell](../../com.aspose.slides/chartdatacell) i dodaje ją do kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Komórka zawierająca nazwę serii. |
| type | int | Ustawia typ serii

--------------------

Jeśli seria wykresu tworzona z tej samej komórki już znajduje się w kolekcji, metoda nic nie dodaje i zwraca jej indeks. |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Dodana seria wykresu lub seria, która już znajduje się w kolekcji.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


Tworzy nową serię wykresu z [ChartCellCollection](../../com.aspose.slides/chartcellcollection) i dodaje ją do kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Komórki zawierające nazwę serii. |
| type | int | Ustawia typ serii

--------------------

Jeśli seria wykresu tworzona z tej samej komórki już znajduje się w kolekcji, metoda nic nie dodaje i zwraca jej indeks. |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Dodana seria wykresu lub seria, która już znajduje się w kolekcji.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```


Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa serii. |
| type | int | Ustawia typ serii |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Dodana seria wykresu.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```


Wyszukuje określony [ChartSeries](../../com.aspose.slides/chartseries) i zwraca indeks zerowy pierwszego wystąpienia w całej Collection

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Wartość serii wykresu. |

**Zwraca:**
int - Indeks zerowy pierwszego wystąpienia podanej wartości w całej CollectionBase, jeśli została znaleziona; w przeciwnym razie -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```


Usuwa podaną wartość.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Wartość. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa kontrolkę ActiveX przechowywaną na określonej pozycji z kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks kontrolki do usunięcia. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie kontrolki z kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```


Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```


Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje całą kolekcję do określonej tablicy.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa |
| index | int | Indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object