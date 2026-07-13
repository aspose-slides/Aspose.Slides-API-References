---
title: ChartDataWorkbook
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller åtkomst till inbäddad Excel-arbetsbok
type: docs
url: /sv/com.aspose.slides/chartdataworkbook/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Tillhandahåller åtkomst till inbäddad Excel-arbetsbok
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Hämtar en samling kalkylblad. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Hämtar uppsättningen av celler. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [clear(int sheetIndex)](#clear-int-) | Rensa alla cellvärden på bladet |
| [calculateFormulas()](#calculateFormulas--) | Beräknar alla formler i arbetsboken och uppdaterar motsvarande cellvärden. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


Hämtar en samling kalkylblad.

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

**Returnerar:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Hämtar uppsättningen av celler.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | java.lang.String | Excel-formel som "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Om true returnerar metoden en samling utan dolda celler. |

**Returnerar:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | java.lang.String | Namnet på kalkylbladet. |
| row | int | Raden. |
| column | int | Kolumnen. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för kalkylbladet. |
| row | int | Raden. |
| column | int | Kolumnen. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för kalkylbladet. |
| cellName | java.lang.String | Namnet på cellen. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för kalkylbladet. |
| cellName | java.lang.String | Namnet på cellen. |
| value | java.lang.Object | Värdet. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för kalkylbladet. |
| row | int | Raden. |
| column | int | Kolumnen. |
| value | java.lang.Object | Värdet. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


Rensa alla cellvärden på bladet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sheetIndex | int | Index för bladet |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Beräknar alla formler i arbetsboken och uppdaterar motsvarande cellvärden.

--------------------

> ```
> Exemplet visar hur man tilldelar en formel till cellen och beräknar ett värde. Värdet i cellen "B4" sätts till 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```
