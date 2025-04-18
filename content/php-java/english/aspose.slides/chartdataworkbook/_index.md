---
title: ChartDataWorkbook
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdataworkbook/
---

## ChartDataWorkbook class

 Provides access to embedded Excel workbook
 
### calculateFormulas {#calculateFormulas}

| Name | Description |
| --- | --- |
| calculateFormulas () | Calculates all formulas in the workbook and updates corresponding cells values. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | CellUnsupportedDataException | Cell data is not supported. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear (int) | Clear all cells values on sheet |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sheetIndex | int | Index of sheet |

 **Returns:**
void


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (String, int, int) | Gets the cell that can be used for chart series or categories |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | Name of the worksheet. |
| row | int | The row. |
| column | int | The column. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, int, int) | Gets the cell that can be used for chart series or categories |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, String) | Gets the cell that can be used for chart series or categories |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | String | Name of the cell. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, String, Object) | Gets the cell that can be used for chart series or categories |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | String | Name of the cell. |
| value | Object | The value. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, int, int, Object) | Gets the cell that can be used for chart series or categories |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |
| value | Object | The value. |

 **Returns:**
[ChartDataCell](../chartdatacell)


---


### getCellCollection {#getCellCollection}

| Name | Description |
| --- | --- |
| getCellCollection (String, boolean) | Gets the set of cells. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| formula | String | Excel formula like "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | If true then method returns collection without hidden cells. |

 **Returns:**
[ChartCellCollection](../chartcellcollection)


---


### getWorksheets {#getWorksheets}

| Name | Description |
| --- | --- |
| getWorksheets () | Gets a collection of worksheets. |

 **Returns:**
[ChartDataWorksheetCollection](../chartdataworksheetcollection)


---


