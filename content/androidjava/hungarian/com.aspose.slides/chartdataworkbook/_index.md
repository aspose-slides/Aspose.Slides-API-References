---
title: ChartDataWorkbook
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Beágyazott Excel munkafüzethez való hozzáférést biztosít
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

Beágyazott Excel munkafüzethez való hozzáférést biztosít
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | A munkalapok gyűjteményét adja vissza. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | A cellák halmazát adja vissza. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza |
| [clear(int sheetIndex)](#clear-int-) | Törli az összes cella értékét a lapon |
| [calculateFormulas()](#calculateFormulas--) | Kiszámítja a munkafüzet összes képletét, és frissíti a megfelelő cellák értékeit. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


A munkalapok gyűjteményét adja vissza.

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


A cellák halmazát adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | Excel képlet, például "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Ha true, akkor a metódus a rejtett cellák nélküli gyűjteményt adja vissza. |

**Visszatérési érték:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza

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


A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza

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


A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza

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


A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza

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


A diagram sorozatokhoz vagy kategóriákhoz felhasználható cellát adja vissza

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
| sheetIndex | int | A lap indexe. |
### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Kiszámítja a munkafüzet összes képletét, és frissíti a megfelelő cellák értékeit.

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