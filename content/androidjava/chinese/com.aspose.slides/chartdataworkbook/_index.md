---
title: ChartDataWorkbook
second_title: Aspose.Slides for Android via Java API 参考
description: 提供对嵌入式 Excel 工作簿的访问
type: docs
url: /zh/com.aspose.slides/chartdataworkbook/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

提供对嵌入式 Excel 工作簿的访问
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | 获取工作表集合。 |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | 获取单元格集合。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | 获取可用于图表系列或类别的单元格 |
| [clear(int sheetIndex)](#clear-int-) | 清除工作表上的所有单元格值 |
| [calculateFormulas()](#calculateFormulas--) | 计算工作簿中的所有公式并更新相应的单元格值。 |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

获取工作表集合。

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

**Returns:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Gets the set of cells.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Excel formula like "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | If true then method returns collection without hidden cells. |

**Returns:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Name of the worksheet. |
| row | int | The row. |
| column | int | The column. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | java.lang.String | Name of the cell. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | java.lang.String | Name of the cell. |
| value | java.lang.Object | The value. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |
| value | java.lang.Object | The value. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Clear all cells values on sheet

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndex | int | Index of sheet |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()


计算工作簿中的所有公式并更新相应的单元格值。

--------------------

> ```
> 示例展示如何为单元格分配公式并计算值。"B4" 单元格的值被设置为 5。
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