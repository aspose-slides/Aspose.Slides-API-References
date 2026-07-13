---
title: IChartSeriesCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie do Java API
description: Reprezentuje kolekcję
type: docs
url: /pl/com.aspose.slides/ichartseriescollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Reprezentuje kolekcję [IChartSeries](../../com.aspose.slides/ichartseries)
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [add(int type)](#add-int-) | Tworzy nową serię wykresu i dodaje ją do kolekcji. |
| [insert(int index, int type)](#insert-int-int-) | Tworzy nową serię wykresu i wstawia ją do kolekcji. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Tworzy nową serię wykresu z [IChartDataCell](../../com.aspose.slides/ichartdatacell) i dodaje ją do kolekcji. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Tworzy nową serię wykresu z [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) i dodaje ją do kolekcji. |
| [add(String name, int type)](#add-java.lang.String-int-) | Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Wyszukuje określony [IChartSeries](../../com.aspose.slides/ichartseries) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Usuwa określoną wartość. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem |
| [clear()](#clear--) | Usuwa wszystkie elementy (w tym styl wykresu) z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Pobiera element pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Element pod określonym indeksem.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Tworzy nową serię wykresu i dodaje ją do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ serii |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nowa seria wykresu.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Tworzy nową serię wykresu i wstawia ją do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks dla wstawienia |
| type | int | Typ wykresu [ChartType](../../com.aspose.slides/charttype) |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nowa seria wykresu [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Tworzy nową serię wykresu z [IChartDataCell](../../com.aspose.slides/ichartdatacell) i dodaje ją do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Komórka zawierająca nazwę serii. |
| type | int | Ustawiony typ serii |

--------------------

Jeśli seria wykresu została utworzona z tej samej komórki już istniejącej w kolekcji, metoda nie dodaje nic i zwraca jej indeks. |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Dodana seria wykresu lub seria, która już znajduje się w kolekcji.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Tworzy nową serię wykresu z [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) i dodaje ją do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Komórki zawierające nazwę serii. |
| type | int | Ustawiony typ serii |

--------------------

Jeśli seria wykresu została utworzona z tej samej komórki już istniejącej w kolekcji, metoda nie dodaje nic i zwraca jej indeks. |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Dodana seria wykresu lub seria, która już znajduje się w kolekcji.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa serii. |
| type | int | Ustawiony typ serii |

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Dodana seria wykresu.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Wyszukuje określony [IChartSeries](../../com.aspose.slides/ichartseries) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Wartość serii wykresu. |

**Zwraca:**
int - Indeks zerowy pierwszego wystąpienia wartości w całej CollectionBase, jeśli znaleziono; w przeciwnym razie -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Usuwa określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Wartość. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element pod określonym indeksem

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks |
### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie elementy (w tym styl wykresu) z kolekcji.