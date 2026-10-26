---
title: ExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /com.aspose.slides/exceldataworkbook/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Represents a workbook that provides access to Excel data for general use.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Initializes a new instance using the specified file path. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Initializes a new instance of the class using the provided stream. |
## Methods

| Method | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Retrieves a collection of cells from the workbook that match the specified formula. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Retrieves a cell from the specified worksheet using its index and cell coordinates. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Retrieves a cell from the specified worksheet using its name and cell coordinates. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook. |
| [getWorksheetNames()](#getWorksheetNames--) | Retrieves the names of all worksheets contained in the Excel workbook. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


Initializes a new instance using the specified file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full path to the Excel workbook file. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


Initializes a new instance of the class using the provided stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream containing the Excel workbook data. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Retrieves a collection of cells from the workbook that match the specified formula.

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
```


Retrieves the names of all worksheets contained in the Excel workbook.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - A list of worksheet names
