---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Tillhandahåller åtkomst till inbäddad Excel-arbetsbok
type: docs
url: /sv/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Tillhandahåller åtkomst till inbäddad Excel-arbetsbok
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Beräknar alla formler i arbetsboken och uppdaterar motsvarande cellvärden. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Hämtar mängden celler. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Hämtar cellen som kan användas för diagramserier eller kategorier |
| [clear(int sheetIndex)](#clear-int-) | Rensa alla cellvärden på bladet |
| [getWorksheets()](#getWorksheets--) | Hämtar en samling av arbetsblad. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


Beräknar alla formler i arbetsboken och uppdaterar motsvarande cellvärden.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Hämtar mängden celler.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | java.lang.String | Excel-formel som "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Om true returnerar metoden en samling utan dolda celler. |

**Returnerar:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Mängd av celler [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | java.lang.String | Namnet på arbetsbladet. |
| row | int | Raden. |
| column | int | Kolumnen. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell objekt
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för arbetsbladet. |
| row | int | Raden. |
| column | int | Kolumnen. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell objekt
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för arbetsbladet. |
| cellName | java.lang.String | Namnet på cellen. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell objekt
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för arbetsbladet. |
| cellName | java.lang.String | Namnet på cellen. |
| value | java.lang.Object | Värdet. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell objekt
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Hämtar cellen som kan användas för diagramserier eller kategorier

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Index för arbetsbladet. |
| row | int | Raden. |
| column | int | Kolumnen. |
| value | java.lang.Object | Värdet. |

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell objekt
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


Rensa alla cellvärden på bladet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sheetIndex | int | Index för bladet |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


Hämtar en samling av arbetsblad.

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