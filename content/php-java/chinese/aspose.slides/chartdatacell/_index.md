---
title: ChartDataCell
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chartdatacell/
---
## ChartDataCell 类

 Represents cell for chart data.
 
### calculate {#calculate}

| 名称 | 描述 |
| --- | --- |
| calculate (boolean) | 如果单元格包含公式，值将基于该公式进行更新。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| updateValues | boolean | 如果为 false，则不执行实际计算。使用 true 以检查可能的异常。 |

 **返回值：**
void


---


### getChartDataWorksheet {#getChartDataWorksheet}

| 名称 | 描述 |
| --- | --- |
| getChartDataWorksheet () | 获取工作表。只读 IChartDataWorksheet。 |

 **返回值：**
[ChartDataWorksheet](../chartdataworksheet)


---


### getColumn {#getColumn}

| 名称 | 描述 |
| --- | --- |
| getColumn () | 返回单元格所在工作表列的索引。只读 int。 |

 **返回值：**
int


---


### getCustomNumberFormat {#getCustomNumberFormat}

| 名称 | 描述 |
| --- | --- |
| getCustomNumberFormat () | 获取或设置数字和日期的自定义显示格式。如果值为空，将使用 PresetNumberFormat 的值。读/写 String。 |

 **返回值：**
String

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 value 为 null，则抛出 ArgumentNullException。 |


---


### getFormula {#getFormula}

| 名称 | 描述 |
| --- | --- |
| getFormula () | 获取或设置 A1 样式的公式。 |

 **返回值：**
String


---


### getPresetNumberFormat {#getPresetNumberFormat}

| 名称 | 描述 |
| --- | --- |
| getPresetNumberFormat () | 获取或设置数字和日期的内置显示格式。预设编号必须在 [0..22] 或 [37..49] 范围内。读/写 byte。 |

 **返回值：**
byte


---


### getR1C1Formula {#getR1C1Formula}

| 名称 | 描述 |
| --- | --- |
| getR1C1Formula () | 获取或设置 R1C1 样式的公式。 |

 **返回值：**
String


---


### getRow {#getRow}

| 名称 | 描述 |
| --- | --- |
| getRow () | 返回单元格所在工作表行的索引。只读 int。 |

 **返回值：**
int


---


### getValue {#getValue}

| 名称 | 描述 |
| --- | --- |
| getValue () | 获取或设置单元格的值。读/写 Object。 |

 **返回值：**
Object


---


### isHidden {#isHidden}

| 名称 | 描述 |
| --- | --- |
| isHidden () | 确定单元格是否隐藏。只读 boolean。 |

 **返回值：**
boolean


---


### setCustomNumberFormat {#setCustomNumberFormat}

| 名称 | 描述 |
| --- | --- |
| setCustomNumberFormat (String) | 获取或设置数字和日期的自定义显示格式。如果值为空，将使用 PresetNumberFormat 的值。读/写 String。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 value 为 null，则抛出 ArgumentNullException。 |


---


### setFormula {#setFormula}

| 名称 | 描述 |
| --- | --- |
| setFormula (String) | 获取或设置 A1 样式的公式。 |

 **返回值：**
void


---


### setPresetNumberFormat {#setPresetNumberFormat}

| 名称 | 描述 |
| --- | --- |
| setPresetNumberFormat (byte) | 获取或设置数字和日期的内置显示格式。预设编号必须在 [0..22] 或 [37..49] 范围内。读/写 byte。 |

 **返回值：**
void


---


### setR1C1Formula {#setR1C1Formula}

| 名称 | 描述 |
| --- | --- |
| setR1C1Formula (String) | 获取或设置 R1C1 样式的公式。 |

 **返回值：**
void


---


### setValue {#setValue}

| 名称 | 描述 |
| --- | --- |
| setValue (Object) | 获取或设置单元格的值。读/写 Object。 |

 **返回值：**
void


---