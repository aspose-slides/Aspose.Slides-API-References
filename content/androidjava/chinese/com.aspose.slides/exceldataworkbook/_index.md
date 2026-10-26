---
title: ExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个工作簿，可用于一般用途的 Excel 数据访问。
type: docs
url: /zh/com.aspose.slides/exceldataworkbook/
---
**继承：**
java.lang.Object

**全部实现的接口：**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

表示一个工作簿，可用于一般用途的 Excel 数据访问。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | 使用指定的文件路径初始化新实例。 |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | 使用提供的流初始化类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 检索与指定公式匹配的工作簿中的单元格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 根据索引和单元格坐标从指定工作表检索单元格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 根据名称和单元格坐标从指定工作表检索单元格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 根据索引和 Excel 样式的单元格名称（如 “B2”）从指定工作表检索单元格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 根据 Excel 样式的单元格名称（如 “B2”）从指定工作表检索单元格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 检索指定工作表中所有图表的索引和名称字典。 |
| [getWorksheetNames()](#getWorksheetNames--) | 检索 Excel 工作簿中包含的所有工作表名称。 |

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

检索与指定公式匹配的工作簿中的单元格集合。

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | A formula or range expression (e.g., "Sheet1!A1:B3") used to identify target cells. |
| skipHiddenCells | boolean | If true, hidden cells (e.g., in hidden rows or columns) will be excluded from the result. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - A read-only list of cells that match the specified formula.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Retrieves a cell from the specified worksheet using its index and cell coordinates.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Zero-based index of the worksheet. |
| row | int | Zero-based row index of the cell. |
| column | int | Zero-based column index of the cell. |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

Retrieves a cell from the specified worksheet using its name and cell coordinates.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | The name of the worksheet. |
| row | int | Zero-based row index of the cell. |
| column | int | Zero-based column index of the cell. |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Zero-based index of the worksheet. |
| cellName | java.lang.String | The Excel-style cell reference (e.g., "A1", "C5"). |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | The name of the worksheet. |
| cellName | java.lang.String | The Excel-style cell reference (e.g., "A1", "C5"). |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | The name of the worksheet to search for charts. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - A dictionary where the key is the chart index and the value is the chart name.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()

检索 Excel 工作簿中包含的所有工作表名称。

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**返回值：**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 包含工作表名称的列表