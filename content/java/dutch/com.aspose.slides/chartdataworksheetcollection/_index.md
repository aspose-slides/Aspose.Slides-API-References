---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de collectie werkbladen van het diagramgegevens-werkboek voor.
type: docs
url: /nl/com.aspose.slides/chartdataworksheetcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Stelt de collectie werkbladen van het diagramgegevens-werkboek voor.

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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het werkblad op index. |
| [size()](#size--) | Retourneert het aantal. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieer naar opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

Retourneert het werkblad op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het werkblad in de collectie. |

**Retourwaarde:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instantie van de IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

Retourneert het aantal. Alleen-lezen int.

**Retourwaarde:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourwaarde:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Kopieer naar opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array om naar te kopiëren. |
| arrayIndex | int | Index om te beginnen met kopiëren. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourwaarde:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourwaarde:**
java.lang.Object