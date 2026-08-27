---
title: ExcelWorkbookImporter
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/excelworkbookimporter/
---
## ExcelWorkbookImporter 类

提供将 Excel 工作簿内容导入到演示文稿的功能。

### addChartFromWorkbook {#addChartFromWorkbook}

| 名称 | 描述 |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  int, boolean) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Excel 工作簿。 |
| worksheetName | String | 包含图表的工作表名称。 |
| chartIndex | int | 要插入的图表形状的基于零的索引。可以使用 IExcelDataWorkbook#getChartsFromWorksheet(String) 方法获取此索引。 |
| embedAllWorkbook | boolean | 如果为 true，则整个工作簿将嵌入图表中；如果为 false，则仅嵌入图表数据。 |

**返回值:**
[Chart](../chart)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当任何必需参数为 null、为空，或在工作簿中找不到图表时抛出。 |

---

### addChartFromWorkbook {#addChartFromWorkbook}

| 名称 | 描述 |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String, boolean) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Excel 工作簿。 |
| worksheetName | String | 包含图表的工作表名称。 |
| chartName | String | 要添加的图表名称。 |
| embedAllWorkbook | boolean | 如果为 true，则整个工作簿将嵌入图表中；如果为 false，则仅嵌入图表数据。 |

**返回值:**
[Chart](../chart)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当任何必需参数为 null、为空，或在工作簿中找不到图表时抛出。 |

---

### addChartFromWorkbook {#addChartFromWorkbook}

| 名称 | 描述 |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, InputStream, String, String,  boolean) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbookStream | InputStream | 包含工作簿数据的流。 |
| worksheetName | String | 包含图表的工作表名称。 |
| chartName | String | 要添加的图表名称。 |
| embedAllWorkbook | boolean | 如果为 true，则整个工作簿将嵌入图表中；如果为 false，则仅嵌入图表数据。 |

**返回值:**
[Chart](../chart)

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当输入数据为不受支持的格式时抛出。 |

---

### addChartFromWorkbook {#addChartFromWorkbook}

| 名称 | 描述 |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String,  boolean) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbookPath | String | 包含图表的工作簿文件路径。 |
| worksheetName | String | 包含图表的工作表名称。 |
| chartName | String | 要添加的图表名称。 |
| embedWorkbook | boolean | 如果为 true，则工作簿将嵌入图表中；如果为 false，则图表将链接到外部工作簿。 |

**返回值:**
[Chart](../chart)

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当输入数据为不受支持的格式时抛出。 |

---

### addTableFromWorkbook {#addTableFromWorkbook}

| 名称 | 描述 |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String) | 从指定的 Excel 工作簿检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | 将添加表格的形状集合。 |
| x | float | 用于定位表格的 X 坐标。 |
| y | float | 用于定位表格的 Y 坐标。 |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Excel 工作簿。 |
| worksheetName | String | 包含表格的工作表名称。 |
| cellRange | String | 定义表格的单元格范围（例如 "A1:D10"）。 |

**返回值:**
[Table](../table)

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当输入数据为不受支持的格式时抛出。 |

---

### addTableFromWorkbook {#addTableFromWorkbook}

| 名称 | 描述 |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String) | 从指定的 Excel 工作簿文件检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | 将添加表格的形状集合。 |
| x | float | 用于定位表格的 X 坐标。 |
| y | float | 用于定位表格的 Y 坐标。 |
| workbookPath | String | Excel 工作簿文件的路径。 |
| worksheetName | String | 包含表格的工作表名称。 |
| cellRange | String | 定义表格的单元格范围（例如 "A1:D10"）。 |

**返回值:**
[Table](../table)

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当输入数据为不受支持的格式时抛出。 |

---

### addTableFromWorkbook {#addTableFromWorkbook}

| 名称 | 描述 |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, InputStream, String, String) | 从指定的 Excel 工作簿文件检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | 将添加表格的形状集合。 |
| x | float | 用于定位表格的 X 坐标。 |
| y | float | 用于定位表格的 Y 坐标。 |
| workbookStream | InputStream | 包含工作簿数据的流。 |
| worksheetName | String | 包含表格的工作表名称。 |
| cellRange | String | 定义表格的单元格范围（例如 "A1:D10"）。 |

**返回值:**
[Table](../table)

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当输入数据为不受支持的格式时抛出。 |

---