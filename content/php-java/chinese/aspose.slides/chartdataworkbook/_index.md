---
title: ChartDataWorkbook
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/chartdataworkbook/
---
## ChartDataWorkbook 类

 提供对嵌入式 Excel 工作簿的访问

### calculateFormulas {#calculateFormulas}

| 名称 | 描述 |
| --- | --- |
| calculateFormulas () | 计算工作簿中的所有公式并更新相应单元格的值。 |

 **返回:**
void

 **Exception**

| 错误 | 条件 |
| --- | --- |
 | CellUnsupportedDataException | 不支持的单元格数据。 |


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear (int) | 清除工作表上的所有单元格值 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sheetIndex | int | 工作表的索引 |

 **返回:**
void


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (String, int, int) | 获取可用于图表系列或类别的单元格 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | String | 工作表的名称。 |
| row | int | 行。 |
| column | int | 列。 |

 **返回:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (int, int, int) | 获取可用于图表系列或类别的单元格 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| row | int | 行。 |
| column | int | 列。 |

 **返回:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (int, String) | 获取可用于图表系列或类别的单元格 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| cellName | String | 单元格的名称。 |

 **返回:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (int, String, Object) | 获取可用于图表系列或类别的单元格 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| cellName | String | 单元格的名称。 |
| value | Object | 值。 |

 **返回:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (int, int, int, Object) | 获取可用于图表系列或类别的单元格 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的索引。 |
| row | int | 行。 |
| column | int | 列。 |
| value | Object | 值。 |

 **返回:**
[ChartDataCell](../chartdatacell)


---


### getCellCollection {#getCellCollection}

| 名称 | 描述 |
| --- | --- |
| getCellCollection (String, boolean) | 获取单元格集合。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| formula | String | Excel 公式，例如 "Sheet1!$A$2:$A$5"。 |
| skipHiddenCells | boolean | 如果为 true，则方法返回不包含隐藏单元格的集合。 |

 **返回:**
[ChartCellCollection](../chartcellcollection)


---


### getWorksheets {#getWorksheets}

| 名称 | 描述 |
| --- | --- |
| getWorksheets () | 获取工作表集合。 |

 **返回:**
[ChartDataWorksheetCollection](../chartdataworksheetcollection)


---