---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Referansı
description: Gömülü Excel çalışma kitabına erişim sağlar
type: docs
url: /tr/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Gömülü Excel çalışma kitabına erişim sağlar
## Yöntemler

| Yöntem | Açıklama |
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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | java.lang.String | Excel formula like "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | If true then method returns collection without hidden cells. |

**Döndürür:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Set of cells [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Gets the cell that can be used for chart series or categories

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | java.lang.String | Name of the worksheet. |
| row | int | The row. |
| column | int | The column. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Gets the cell that can be used for chart series or categories

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Gets the cell that can be used for chart series or categories

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | java.lang.String | Name of the cell. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Gets the cell that can be used for chart series or categories

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | java.lang.String | Name of the cell. |
| value | java.lang.Object | The value. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Gets the cell that can be used for chart series or categories

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |
| value | java.lang.Object | The value. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell nesnesi
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


Clear all cells values on sheet

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sheetIndex | int | Index of sheet |

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

**Döndürür:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)