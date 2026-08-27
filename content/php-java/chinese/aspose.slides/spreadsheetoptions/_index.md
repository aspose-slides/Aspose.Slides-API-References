---
title: SpreadsheetOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/spreadsheetoptions/
---
## SpreadsheetOptions 类

 表示可用于指定其他电子表格行为的选项。
 
### SpreadsheetOptions {#SpreadsheetOptions}

| 名称 | 描述 |
| --- | --- |
| SpreadsheetOptions() | 初始化 SpreadsheetOptions 类的新实例。 |

 **返回：**
SpreadsheetOptions


---


### getPreferredCulture {#getPreferredCulture}

| 名称 | 描述 |
| --- | --- |
| getPreferredCulture () | 获取或设置首选文化信息，以计算专为使用双字节字符集（DBCS）的语言设计的某些函数。 |

 **返回：**
Locale


---


### getRecoverWorkbookFromChartCache {#getRecoverWorkbookFromChartCache}

| 名称 | 描述 |
| --- | --- |
| getRecoverWorkbookFromChartCache () | 如果图表的数据源是外部工作簿且不可用，则将从图表缓存中恢复。 |

 **返回：**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | InvalidOperationException | 当外部工作簿不可用且 RecoverWorkbookFromChartCache 属性值为 false 时抛出此异常。 |


---


### setPreferredCulture {#setPreferredCulture}

| 名称 | 描述 |
| --- | --- |
| setPreferredCulture (Locale) | 获取或设置首选文化信息，以计算专为使用双字节字符集（DBCS）的语言设计的某些函数。 |

 **返回：**
void


---


### setRecoverWorkbookFromChartCache {#setRecoverWorkbookFromChartCache}

| 名称 | 描述 |
| --- | --- |
| setRecoverWorkbookFromChartCache (boolean) | 如果图表的数据源是外部工作簿且不可用，则将从图表缓存中恢复。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | InvalidOperationException | 当外部工作簿不可用且 RecoverWorkbookFromChartCache 属性值为 false 时抛出此异常。 |


---