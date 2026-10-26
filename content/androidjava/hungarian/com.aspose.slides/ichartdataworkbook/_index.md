---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android Java API-referencia
description: Beágyazott Excel munkafüzet elérését biztosítja
type: docs
url: /hu/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Beágyazott Excel munkafüzet elérését biztosítja
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Kiszámítja a munkafüzet összes képletét, és frissíti a megfelelő cellák értékeit. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Lekéri a cellák halmazát. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát |
| [clear(int sheetIndex)](#clear-int-) | Törli az összes cella értékét a lapon |
| [getWorksheets()](#getWorksheets--) | Lekéri a munkalapok gyűjteményét. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Lekéri a cellák halmazát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | Excel képlet, például "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Ha igaz, a metódus a rejtett cellákat kihagyó gyűjteményt ad vissza. |

**Visszatérési érték:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Set of cells [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát

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
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát

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
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | int | A munkalap indexe. |
| cellName | java.lang.String | A cella neve. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát

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
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Lekéri a diagram sorozathoz vagy kategóriákhoz használható cellát

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
public abstract void clear(int sheetIndex)
```


Törli az összes cella értékét a lapon

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sheetIndex | int | A lap indexe |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


Lekéri a munkalapok gyűjteményét.

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