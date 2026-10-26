---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: 提供对嵌入式 Excel 工作簿的访问
type: docs
url: /zh/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

提供对嵌入式 Excel 工作簿的访问
## 方法

| 方法 | 描述 |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | 计算工作簿中的所有公式并更新相应单元格的值。 |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | 获取单元格集合。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | 获取可用于图表系列或类别的单元格 |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | 获取可用于图表系列或类别的单元格 |
| [clear(int sheetIndex)](#clear-int-) | 清除工作表上所有单元格的值 |
| [getWorksheets()](#getWorksheets--) | 获取工作表集合。 |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


计算工作簿中的所有公式并更新相应单元格的值。

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


获取单元格集合。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | java.lang.String | Excel 公式，例如 "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | 如果为 true，则方法返回不包含隐藏单元格的集合。 |

**返回：**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - 单元格集合 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


获取可用于图表系列或类别的单元格

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名称。 |
| row | int | 行号。 |
| column | int | 列号。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 单元格对象
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


获取可用于图表系列或类别的单元格

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| row | int | 行号。 |
| column | int | 列号。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 单元格对象
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


获取可用于图表系列或类别的单元格

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| cellName | java.lang.String | 单元格名称。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 单元格对象
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


获取可用于图表系列或类别的单元格

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| cellName | java.lang.String | 单元格名称。 |
| value | java.lang.Object | 值。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 单元格对象
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


获取可用于图表系列或类别的单元格

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| row | int | 行号。 |
| column | int | 列号。 |
| value | java.lang.Object | 值。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 单元格对象
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


清除工作表上所有单元格的值

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sheetIndex | int | 工作表的索引 |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
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

**返回：**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)