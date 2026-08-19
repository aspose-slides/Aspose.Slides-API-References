---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides pro Java – dokumentace API
description: Představuje kolekci listů pracovního sešitu dat grafu.
type: docs
url: /cs/com.aspose.slides/chartdataworksheetcollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Představuje kolekci listů pracovního sešitu dat grafu.

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

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrátí list podle indexu. |
| [size()](#size--) | Vrátí počet. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Vrátí iterátor java pro celou kolekci. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrátí hodnotu určující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrátí kořen synchronizace. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```


Vrátí list podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index pracovního listu v kolekci. |

**Návratová hodnota:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instance třídy IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```


Vrátí počet. Pouze pro čtení int.

**Návratová hodnota:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrátí objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Návratová hodnota:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```


Vrátí iterátor java pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```


Vrátí enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator that can be used to iterate through the collection.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


Zkopíruje do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole, do kterého se má kopírovat. |
| arrayIndex | int | Index, od kterého se má začít kopírovat. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrátí hodnotu určující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Návratová hodnota:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrátí kořen synchronizace. Pouze pro čtení Object.

**Návratová hodnota:**
java.lang.Object