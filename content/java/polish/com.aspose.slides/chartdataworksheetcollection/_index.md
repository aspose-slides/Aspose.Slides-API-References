---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kolekcję arkuszy skoroszytu danych wykresu.
type: docs
url: /pl/com.aspose.slides/chartdataworksheetcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheet, IDOMObject
```

Reprezentuje kolekcję arkuszy roboczych skoroszytu danych wykresu.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca arkusz roboczy według indeksu. |
| [size()](#size--) | Zwraca liczbę. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuj do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

Zwraca arkusz roboczy według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks arkusza w kolekcji. |

**Zwraca:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instancja IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

Zwraca liczbę. Tylko do odczytu int.

**Zwraca:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Kopiuj do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica, do której kopiować. |
| arrayIndex | int | Indeks, od którego rozpocząć kopiowanie. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object