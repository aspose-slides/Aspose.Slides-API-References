---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: 表示一个工作簿，可用于通用访问 Excel 数据。
type: docs
url: /zh/com.aspose.slides/iexceldataworkbook/
---
```
public interface IExcelDataWorkbook
```

表示一个工作簿，可用于通用访问 Excel 数据。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 检索工作簿中匹配指定公式的单元格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 使用索引和单元格坐标从指定工作表检索单元格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 使用工作表名称和单元格坐标从指定工作表检索单元格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 使用索引和 Excel 样式的单元格名称（例如 "B2"）从指定工作表检索单元格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 使用 Excel 样式的单元格名称（例如 "B2"）从指定工作表检索单元格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 检索包含 Excel 工作簿中指定工作表的所有图表的索引和名称的字典。 |
| [getWorksheetNames()](#getWorksheetNames--) | 检索 Excel 工作簿中包含的所有工作表的名称。 |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

检索工作簿中匹配指定公式的单元格集合。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
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
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
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
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
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
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
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
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
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
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
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
public abstract System.Collections.Generic.List<String> getWorksheetNames()

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 工作表名称的列表