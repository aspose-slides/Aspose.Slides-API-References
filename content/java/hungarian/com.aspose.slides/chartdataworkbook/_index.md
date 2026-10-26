---
title: ChartDataWorkbook
second_title: Aspose.Slides for Java API-referencia
description: Beágyazott Excel munkafüzethez biztosít hozzáférést
type: docs
url: /hu/com.aspose.slides/chartdataworkbook/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Provides access to embedded Excel workbook
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Lekér egy munkalapok gyűjteményét. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Lekér a cellák halmazát. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható |
| [clear(int sheetIndex)](#clear-int-) | Törli az összes cella értékét a lapon |
| [calculateFormulas()](#calculateFormulas--) | Kiszámítja a munkafüzet összes képletét, és frissíti a megfelelő cellaértékeket. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


Lekér egy munkalapok gyűjteményét.

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

**Visszatérési érték:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Lekér a cellák halmazát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | Excel képlet, például "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Ha igaz, a metódus rejtett cellák nélkül adja vissza a gyűjteményt. |

**Visszatérési érték:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | java.lang.String | A munkalap neve. |
| row | int | A sor. |
| column | int | Az oszlop. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | int | A munkalap indexe. |
| row | int | A sor. |
| column | int | Az oszlop. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | int | A munkalap indexe. |
| cellName | java.lang.String | A cella neve. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | int | A munkalap indexe. |
| cellName | java.lang.String | A cella neve. |
| value | java.lang.Object | Az érték. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Lekérja a cellát, amely diagram sorozatokhoz vagy kategóriákhoz használható

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | int | A munkalap indexe. |
| row | int | A sor. |
| column | int | Az oszlop. |
| value | java.lang.Object | Az érték. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


Törli az összes cella értékét a lapon

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sheetIndex | int | A lap indexe |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Kiszámítja a munkafüzet összes képletét, és frissíti a megfelelő cellaértékeket.

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