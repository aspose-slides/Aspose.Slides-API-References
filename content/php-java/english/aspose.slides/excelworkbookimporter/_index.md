---
title: ExcelWorkbookImporter
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/excelworkbookimporter/
---

## ExcelWorkbookImporter class

 Provides functionality for importing content from an Excel workbook into a presentation.
 
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
| chartIndex | int | The zero-based index of the chart shape to insert. This index can be obtained using the IExcelDataWorkbook#getChartsFromWorksheet(String) method. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |

 **Returns:**
[Chart](../chart)

 **Exception**

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

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when any required parameter is null, empty, or if the chart cannot be found in the workbook. |


---


### addChartFromWorkbook {#addChartFromWorkbook}

| Name | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, InputStream, String, String,  boolean) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbookStream | InputStream | A stream containing the workbook data. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartName | String | The name of the chart to be added. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |

 **Returns:**
[Chart](../chart)

 **Exception**

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

 **Exception**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when the input data is in an unsupported format. |


---


