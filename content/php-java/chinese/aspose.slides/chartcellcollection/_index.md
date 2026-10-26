---
title: ChartCellCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chartcellcollection/
---
## ChartCellCollection 类

 表示包含数据的单元格集合。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([ChartDataCell](../chartdatacell)) | 向集合中添加新单元格。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| cell | [ChartDataCell](../chartdatacell) | 要添加的新单元格。 |

**返回值：**
void


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (Object) | 从指定值创建 ChartDataCell 并将其添加到集合中。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | Object | 值。此方法添加名为 AUTO_DATA 的工作表并在其中添加所有值。如果使用 ChartDataWorkbook 添加或编辑 Cell 值，请确保不使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。 |

**返回值：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.InvalidOperationException | 如果超过限制 |


---


### getCellsAddress {#getCellsAddress}

| 名称 | 描述 |
| --- | --- |
| getCellsAddress () | 返回工作簿中单元格集合的地址。 |

**返回值：**
String


---


### getConcatenatedValuesFromCells {#getConcatenatedValuesFromCells}

| 名称 | 描述 |
| --- | --- |
| getConcatenatedValuesFromCells () | 从所有单元格的字符串值连接而成的字符串。 |

**返回值：**
String


---


### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 获取集合中单元格的计数。只读 int。 |

**返回值：**
int


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 根据索引返回一个单元格 (IChartDataCell)。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 单元格的索引。 |

**返回值：**
[ChartDataCell](../chartdatacell)


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

**返回值：**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回值：**



---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 通过索引从集合中移除单元格。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的单元格的索引。 |

**返回值：**
void


---