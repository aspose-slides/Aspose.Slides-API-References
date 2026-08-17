---
title: ExcelDataWorkbook
second_title: Aspose.Slides for Java API 参考
description: 表示一个工作簿，可供一般使用访问 Excel 数据。
type: docs
url: /zh/com.aspose.slides/exceldataworkbook/
---
**继承:**
java.lang.Object

**所有已实现的接口:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

表示一个工作簿，可供一般使用访问 Excel 数据。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | 使用指定的文件路径初始化新实例。 |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | 使用提供的流初始化类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 检索工作簿中与指定公式匹配的单元格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 使用索引和单元格坐标从指定的工作表中检索单元格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 使用名称和单元格坐标从指定的工作表中检索单元格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 使用索引和 Excel 样式的单元格名称（如 "B2"）从指定的工作表中检索单元格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 使用 Excel 样式的单元格名称（如 "B2"）从指定的工作表中检索单元格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 检索包含 Excel 工作簿中指定工作表的所有图表的索引和名称的字典。 |
| [getWorksheetNames()](#getWorksheetNames--) | 检索 Excel 工作簿中包含的所有工作表的名称。 |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

使用指定的文件路径初始化新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | Excel 工作簿文件的完整路径。 |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

使用提供的流初始化类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 Excel 工作簿数据的流。 |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

检索工作簿中与指定公式匹配的单元格集合。

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //输出: 5
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | java.lang.String | 用于标识目标单元格的公式或范围表达式（例如 "Sheet1!A1:B3"）。 |
| skipHiddenCells | boolean | 如果为 true，则隐藏的单元格（例如隐藏的行或列中的单元格）将从结果中排除。 |

**返回值：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 只读的与指定公式匹配的单元格列表。

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

使用索引和单元格坐标从指定的工作表中检索单元格。

--------------------

> ```
> 示例：
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的从零开始的索引。 |
| row | int | 单元格的从零开始的行索引。 |
| column | int | 单元格的从零开始的列索引。 |

**返回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

使用工作表名称和单元格坐标从指定的工作表中检索单元格。

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
| row | int | 单元格的从零开始的行索引。 |
| column | int | 单元格的从零开始的列索引。 |

**返回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

使用索引和 Excel 样式的单元格名称（例如 "B2"）从指定的工作表中检索单元格。

--------------------

> ```
> 示例：
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的从零开始的索引。 |
| cellName | java.lang.String | Excel 样式的单元格引用（例如 "A1", "C5"）。 |

**返回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

使用 Excel 样式的单元格名称（例如 "B2"）从指定的工作表中检索单元格。

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
| cellName | java.lang.String | Excel 样式的单元格引用（例如 "A1", "C5"）。 |

**返回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的单元格。

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

检索包含 Excel 工作簿中指定工作表的所有图表的索引和名称的字典。

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
| worksheetName | java.lang.String | 要搜索图表的工作表名称。 |

**返回值：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - 一个字典，其中键是图表索引，值是图表名称。

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

检索 Excel 工作簿中包含的所有工作表的名称。

--------------------

> ```
> 示例：
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```


**返回值：**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 工作表名称列表