---
title: ChartDataWorkbook
second_title: Aspose.Slides for Java API 參考
description: 提供對嵌入式 Excel 活頁簿的存取
type: docs
url: /zh-hant/com.aspose.slides/chartdataworkbook/
---
**繼承關係:**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

提供對嵌入式 Excel 活頁簿的存取
## 方法

| 方法 | 說明 |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | 取得工作表的集合。 |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | 取得儲存格集合。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 取得可用於圖表序列或類別的儲存格 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 取得可用於圖表序列或類別的儲存格 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 取得可用於圖表序列或類別的儲存格 |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | 取得可用於圖表序列或類別的儲存格 |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | 取得可用於圖表序列或類別的儲存格 |
| [clear(int sheetIndex)](#clear-int-) | 清除工作表上所有儲存格的值 |
| [calculateFormulas()](#calculateFormulas--) | 計算活頁簿中所有公式並更新相應儲存格的值。 |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
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

**傳回:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


取得儲存格集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | Excel 公式，例如 "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | 若為 true，則方法回傳不含隱藏儲存格的集合。 |

**傳回:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


取得可用於圖表序列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表名稱。 |
| row | int | 列號。 |
| column | int | 欄號。 |

**傳回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 物件
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


取得可用於圖表序列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表索引。 |
| row | int | 列號。 |
| column | int | 欄號。 |

**傳回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 物件
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


取得可用於圖表序列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表索引。 |
| cellName | java.lang.String | 儲存格名稱。 |

**傳回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 物件
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


取得可用於圖表序列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表索引。 |
| cellName | java.lang.String | 儲存格名稱。 |
| value | java.lang.Object | 值。 |

**傳回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 物件
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


取得可用於圖表序列或類別的儲存格

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表索引。 |
| row | int | 列號。 |
| column | int | 欄號。 |
| value | java.lang.Object | 值。 |

**傳回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 物件
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


清除工作表上所有儲存格的值

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sheetIndex | int | 工作表索引。 |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


計算活頁簿中所有公式並更新相應儲存格的值。

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