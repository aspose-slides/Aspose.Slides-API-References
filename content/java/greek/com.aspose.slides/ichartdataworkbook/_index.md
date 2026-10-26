---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Παρέχει πρόσβαση σε ενσωματωμένο βιβλίο εργασίας Excel
type: docs
url: /el/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Παρέχει πρόσβαση σε ενσωματωμένο βιβλίο εργασίας Excel
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Calculates all formulas in the workbook and updates corresponding cells values. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Gets the set of cells. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Gets the cell that can be used for chart series or categories |
| [clear(int sheetIndex)](#clear-int-) | Clear all cells values on sheet |
| [getWorksheets()](#getWorksheets--) | Gets a collection of worksheets. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


Calculates all formulas in the workbook and updates corresponding cells values.

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


Gets the set of cells.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Τύπος Excel όπως "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Εάν είναι true, η μέθοδος επιστρέφει τη συλλογή χωρίς κρυμμένα κελιά. |

**Επιστρέφει:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Set of cells [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Gets the cell that can be used for chart series or categories

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Όνομα του φύλλου εργασίας. |
| row | int | Η γραμμή. |
| column | int | Η στήλη. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Gets the cell that can be used for chart series or categories

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| row | int | Η γραμμή. |
| column | int | Η στήλη. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Gets the cell that can be used for chart series or categories

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| cellName | java.lang.String | Όνομα του κελιού. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Gets the cell that can be used for chart series or categories

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| cellName | java.lang.String | Όνομα του κελιού. |
| value | java.lang.Object | Η τιμή. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Gets the cell that can be used for chart series or categories

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| row | int | Η γραμμή. |
| column | int | Η στήλη. |
| value | java.lang.Object | Η τιμή. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


Clear all cells values on sheet

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndex | int | Δείκτης του φύλλου |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


Gets a collection of worksheets.

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


**Επιστρέφει:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)