---
title: ExcelWorkbookImporter
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/excelworkbookimporter/
---

## ExcelWorkbookImporter class

 Provides functionality for importing content from an Excel workbook into a presentation.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
[WORKSHEET_NAME](#WORKSHEET_NAME) | worksheetName |  |


---


### WORKSHEET_NAME {#WORKSHEET_NAME}


---


### addChartFromWorkbook {#addChartFromWorkbook}

| Name | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  int, boolean) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | The Excel workbook. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartIndex | int | The zero-based index of the chart shape to insert. This index can be obtained using the IExcelDataWorkbook#getChartsFromWorksheet(String) function. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |

 **Returns:**
[Chart](../chart)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when any required parameter is null, empty, or if the chart cannot be found in the workbook. |


---


### addChartFromWorkbook {#addChartFromWorkbook}

| Name | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String, boolean) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | The Excel workbook. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartName | String | The name of the chart to be added. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |

 **Returns:**
[Chart](../chart)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when any required parameter is null, empty, or if the chart cannot be found in the workbook. |


---


### addChartFromWorkbookFromStream  {#addChartFromWorkbookFromStream }

| Name | Description |
| --- | --- |
| addChartFromWorkbookFromStream  (ExcelWorkbookImporter, [ShapeCollection](../shapecollection), float,  float, ReadStream, String, String, boolean, Function) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| excelworkbookimporter | ExcelWorkbookImporter  | link to self |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbookStream | ReadStream | A stream containing the workbook data. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartName | String | The name of the chart to be added. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[Chart](../chart)

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when the input data is in an unsupported format. |


---


### addChartFromWorkbook {#addChartFromWorkbook}

| Name | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String,  boolean) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbookPath | String | The file path to the workbook containing the chart. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartName | String | The name of the chart to be added. |
| embedWorkbook | boolean | If true, the workbook will be embedded in the chart; if false, the chart will link to the external workbook. |

 **Returns:**
[Chart](../chart)

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when the input data is in an unsupported format. |


---


### addTableFromWorkbook {#addTableFromWorkbook}

| Name | Description |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String) | Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the table will be added. |
| x | float | The X coordinate for positioning the table. |
| y | float | The Y coordinate for positioning the table. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | The Excel workbook. |
| worksheetName | String | The name of the worksheet that contains the table. |
| cellRange | String | The cell range that defines the table (for example, "A1:D10"). |

 **Returns:**
[Table](../table)

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when the input data is in an unsupported format. |


---


### addTableFromWorkbook {#addTableFromWorkbook}

| Name | Description |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String) | Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the table will be added. |
| x | float | The X coordinate for positioning the table. |
| y | float | The Y coordinate for positioning the table. |
| workbookPath | String | The path to the Excel workbook file. |
| worksheetName | String | The name of the worksheet that contains the table. |
| cellRange | String | The cell range that defines the table (for example, "A1:D10"). |

 **Returns:**
[Table](../table)

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when the input data is in an unsupported format. |


---


### addTableFromWorkbookFromStream  {#addTableFromWorkbookFromStream }

| Name | Description |
| --- | --- |
| addTableFromWorkbookFromStream  (ExcelWorkbookImporter, [ShapeCollection](../shapecollection), float,  float, ReadStream, String, String, Function) | Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| excelworkbookimporter | ExcelWorkbookImporter  | link to self |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the table will be added. |
| x | float | The X coordinate for positioning the table. |
| y | float | The Y coordinate for positioning the table. |
| workbookStream | ReadStream | A stream containing the workbook data. |
| worksheetName | String | The name of the worksheet that contains the table. |
| cellRange | String | The cell range that defines the table (for example, "A1:D10"). |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[Table](../table)

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when the input data is in an unsupported format. |


---


