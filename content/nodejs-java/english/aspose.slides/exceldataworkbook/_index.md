---
title: ExcelDataWorkbook
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/exceldataworkbook/
---

## ExcelDataWorkbook class

 Represents a workbook that provides access to Excel data for general use.
 
### ExcelDataWorkbook {#ExcelDataWorkbook}

| Name | Description |
| --- | --- |
| ExcelDataWorkbook(String) | Initializes a new instance using the specified file path. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The full path to the Excel workbook file. |

 **Returns:**
ExcelDataWorkbook

 **Error**

| Error | Condition |
| --- | --- |
 | FileNotFoundException | Thrown when the specified file does not exist. |


---


### createExcelDataWorkbookFromStream  {#createExcelDataWorkbookFromStream }

| Name | Description |
| --- | --- |
| createExcelDataWorkbookFromStream (ReadStream, Function) | Initializes a new instance of the class using the provided stream. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | A stream containing the Excel workbook data. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the ExcelDataWorkbook |

 **Returns:**
ExcelDataWorkbook


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, int, int) | Retrieves a cell from the specified worksheet using its index and cell coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Zero-based index of the worksheet. |
| row | int | Zero-based row index of the cell. |
| column | int | Zero-based column index of the cell. |

 **Returns:**
[ExcelDataCell](../exceldatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (String, int, int) | Retrieves a cell from the specified worksheet using its name and cell coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | The name of the worksheet. |
| row | int | Zero-based row index of the cell. |
| column | int | Zero-based column index of the cell. |

 **Returns:**
[ExcelDataCell](../exceldatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, String) | Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2"). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Zero-based index of the worksheet. |
| cellName | String | The Excel-style cell reference (e.g., "A1", "C5"). |

 **Returns:**
[ExcelDataCell](../exceldatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (String, String) | Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2"). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | The name of the worksheet. |
| cellName | String | The Excel-style cell reference (e.g., "A1", "C5"). |

 **Returns:**
[ExcelDataCell](../exceldatacell)


---


### getCells {#getCells}

| Name | Description |
| --- | --- |
| getCells (String, boolean) | Retrieves a collection of cells from the workbook that match the specified formula. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| formula | String | A formula or range expression (e.g., "Sheet1!A1:B3") used to identify target cells. |
| skipHiddenCells | boolean | If true, hidden cells (e.g., in hidden rows or columns) will be excluded from the result. |

 **Returns:**
ArrayList, List


---


### getChartsFromWorksheet {#getChartsFromWorksheet}

| Name | Description |
| --- | --- |
| getChartsFromWorksheet (String) | Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | The name of the worksheet to search for charts. |

 **Returns:**
Dictionary


---


### getWorksheetNames {#getWorksheetNames}

| Name | Description |
| --- | --- |
| getWorksheetNames () | Retrieves the names of all worksheets contained in the Excel workbook. |

 **Returns:**
ArrayList, List


---


