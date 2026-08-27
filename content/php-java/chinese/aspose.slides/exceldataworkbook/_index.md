---
title: ExcelDataWorkbook
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/exceldataworkbook/
---
## ExcelDataWorkbook 类

 表示一个工作簿，可供一般使用时访问 Excel 数据。

### ExcelDataWorkbook {#ExcelDataWorkbook}

| 名称 | 描述 |
| --- | --- |
| ExcelDataWorkbook(String) | 使用指定的文件路径初始化新实例。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | Excel 工作簿文件的完整路径。 |

**返回:**
ExcelDataWorkbook

**错误**

| 错误 | 条件 |
| --- | --- |
| FileNotFoundException | 当指定的文件不存在时抛出。 |


---


### ExcelDataWorkbook {#ExcelDataWorkbook}

| 名称 | 描述 |
| --- | --- |
| ExcelDataWorkbook(InputStream) | 使用提供的流初始化类的新实例。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 包含 Excel 工作簿数据的流。 |

**返回:**
ExcelDataWorkbook


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (int, int, int) | 从指定的工作表中检索单元格，使用其索引和单元格坐标。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| row | int | 单元格的零基行索引。 |
| column | int | 单元格的零基列索引。 |

**返回:**
[ExcelDataCell](../exceldatacell)


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (String, int, int) | 从指定的工作表中检索单元格，使用其名称和单元格坐标。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | String | 工作表的名称。 |
| row | int | 单元格的零基行索引。 |
| column | int | 单元格的零基列索引。 |

**返回:**
[ExcelDataCell](../exceldatacell)


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (int, String) | 从指定的工作表中检索单元格，使用其索引和 Excel 风格的单元格名称（例如 "B2"）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| cellName | String | Excel 风格的单元格引用（例如 "A1", "C5"）。 |

**返回:**
[ExcelDataCell](../exceldatacell)


---


### getCell {#getCell}

| 名称 | 描述 |
| --- | --- |
| getCell (String, String) | 从指定的工作表中检索单元格，使用 Excel 风格的单元格名称（例如 "B2"）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | String | 工作表的名称。 |
| cellName | String | Excel 风格的单元格引用（例如 "A1", "C5"）。 |

**返回:**
[ExcelDataCell](../exceldatacell)


---


### getCells {#getCells}

| 名称 | 描述 |
| --- | --- |
| getCells (String, boolean) | 检索工作簿中与指定公式匹配的单元格集合。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| formula | String | 用于标识目标单元格的公式或范围表达式（例如 "Sheet1!A1:B3"）。 |
| skipHiddenCells | boolean | 如果为 true，将从结果中排除隐藏的单元格（例如在隐藏的行或列中）。 |

**返回:**
ArrayList, List


---


### getChartsFromWorksheet {#getChartsFromWorksheet}

| 名称 | 描述 |
| --- | --- |
| getChartsFromWorksheet (String) | 检索字典，包含 Excel 工作簿中指定工作表的所有图表的索引和名称。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| worksheetName | String | 要搜索图表的工作表名称。 |

**返回:**
Dictionary


---


### getWorksheetNames {#getWorksheetNames}

| 名称 | 描述 |
| --- | --- |
| getWorksheetNames () | 检索 Excel 工作簿中包含的所有工作表的名称。 |

**返回:**
ArrayList, List


---