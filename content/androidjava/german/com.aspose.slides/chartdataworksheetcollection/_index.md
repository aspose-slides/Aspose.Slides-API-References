---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt die Sammlung von Arbeitsblättern des Diagrammdaten-Arbeitsbuchs dar.
type: docs
url: /de/com.aspose.slides/chartdataworksheetcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Stellt die Sammlung von Arbeitsblättern des Diagrammdaten-Arbeitsbuchs dar.

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

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Arbeitsblatt nach Index zurück. |
| [size()](#size--) | Gibt die Anzahl zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Gibt eine Synchronisationswurzel zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```


Gibt das Arbeitsblatt nach Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Arbeitsblatts in der Sammlung. |

**Rückgabewert:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instanz von IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl zurück. Nur lesbar int.

**Rückgabewert:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


Kopiert in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array, in das kopiert wird. |
| arrayIndex | int | Index, ab dem das Kopieren beginnt. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-safe). Nur lesbar boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt eine Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabewert:**
java.lang.Object