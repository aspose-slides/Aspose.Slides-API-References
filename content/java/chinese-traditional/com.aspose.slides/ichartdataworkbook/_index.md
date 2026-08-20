---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: 提供對嵌入式 Excel 工作簿的存取
type: docs
url: /zh-hant/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

提供對嵌入式 Excel 工作簿的存取
## 方法

| 方法 | 說明 |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | 計算工作簿中的所有公式並更新相應的儲存格值。 |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | 取得儲存格集合。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 取得可用於圖表系列或類別的儲存格 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 取得可用於圖表系列或類別的儲存格 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 取得可用於圖表系列或類別的儲存格 |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | 取得可用於圖表系列或類別的儲存格 |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | 取得可用於圖表系列或類別的儲存格 |
| [clear(int sheetIndex)](#clear-int-) | 清除工作表上所有儲存格的值 |
| [getWorksheets()](#getWorksheets--) | 取得工作表的集合。 |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

計算工作簿中的所有公式並更新相應的儲存格值。

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

取得儲存格集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | Excel 公式，例如 "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | 如果為 true，則方法返回不含隱藏儲存格的集合。 |

**返回:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - 儲存格集合 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

取得可用於圖表系列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名稱。 |
| row | int | 行。 |
| column | int | 列。 |

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 儲存格物件
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

取得可用於圖表系列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| row | int | 行。 |
| column | int | 列。 |

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 儲存格物件
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

取得可用於圖表系列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| cellName | java.lang.String | 儲存格的名稱。 |

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 儲存格物件
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

取得可用於圖表系列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| cellName | java.lang.String | 儲存格的名稱。 |
| value | java.lang.Object | 值。 |

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 儲存格物件
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

取得可用於圖表系列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| row | int | 行。 |
| column | int | 列。 |
| value | java.lang.Object | 值。 |

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 儲存格物件
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

清除工作表上所有儲存格的值

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sheetIndex | int | 工作表的索引 |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

取得工作表的集合。

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

**返回:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)