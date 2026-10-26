---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /zh/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

表示一个工作簿，提供对一般用途的 Excel 数据的访问。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 检索工作簿中与指定公式匹配的单元格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 使用索引和单元格坐标从指定的工作表检索单元格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 使用名称和单元格坐标从指定的工作表检索单元格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 使用索引和 Excel 样式的单元格名称（例如 “B2”）从指定的工作表检索单元格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 使用 Excel 样式的单元格名称（例如 “B2”）从指定的工作表检索单元格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 检索包含 Excel 工作簿中指定工作表所有图表的索引和名称的字典。 |
| [getWorksheetNames()](#getWorksheetNames--) | 检索 Excel 工作簿中包含的所有工作表的名称。 |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

检索工作簿中与指定公式匹配的单元格集合。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //输出: 5
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | java.lang.String | 用于标识目标单元格的公式或范围表达式（例如 “Sheet1!A1:B3”）。 |
| skipHiddenCells | boolean | 如果为 true，将在结果中排除隐藏的单元格（例如隐藏的行或列中的单元格）。 |

**返回：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 只读列表，包含与指定公式匹配的单元格。

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

使用索引和单元格坐标从指定的工作表检索单元格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| row | int | 单元格的零基行索引。 |
| column | int | 单元格的零基列索引。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

使用名称和单元格坐标从指定的工作表检索单元格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名称。 |
| row | int | 单元格的零基行索引。 |
| column | int | 单元格的零基列索引。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

使用索引和 Excel 样式的单元格名称（例如 “B2”）从指定的工作表检索单元格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| cellName | java.lang.String | Excel 样式的单元格引用（例如 “A1”、 “C5”）。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

使用名称和 Excel 样式的单元格名称（例如 “B2”）从指定的工作表检索单元格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名称。 |
| cellName | java.lang.String | Excel 样式的单元格引用（例如 “A1”、 “C5”）。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

检索 Excel 工作簿中指定工作表所有图表的索引和名称的字典。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | java.lang.String | 用于搜索图表的工作表名称。 |

**返回：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - 字典，其中键是图表索引，值是图表名称。

### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

检索 Excel 工作簿中包含的所有工作表的名称。

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**返回：**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 工作表名称列表。