---
title: ChartSeriesCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chartseriescollection/
---
## ChartSeriesCollection 类

 表示 ChartSeries 的集合
 
### add {#add}

| Name | Description |
| --- | --- |
| add (int) | 创建新的图表序列并将其添加到集合中。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| type | int | 序列的类型 |

 **返回值：**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell), int) | 从 ChartDataCell 创建新的图表序列并将其添加到集合中。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [ChartDataCell](../chartdatacell) | 包含序列名称的单元格。 |
| type | int | 设置序列类型。如果从同一单元格创建的图表序列已在集合中，则方法不执行任何操作并返回其索引。 |

 **返回值：**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartCellCollection](../chartcellcollection), int) | 从 ChartCellCollection 创建新的图表序列并将其添加到集合中。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [ChartCellCollection](../chartcellcollection) | 包含序列名称的单元格集合。 |
| type | int | 设置序列类型。如果从同一单元格创建的图表序列已在集合中，则方法不执行任何操作并返回其索引。 |

 **返回值：**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, int) | 根据值创建新的图表序列并将其添加到集合中。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 序列名称。 |
| type | int | 设置序列的类型 |

 **返回值：**
[ChartSeries](../chartseries)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | 从集合中移除所有控件。 |

 **返回值：**
void


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回值：**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。 |

 **返回值：**
[ChartSeries](../chartseries)

 **异常**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | 索引在 IList 中不是有效索引。 |


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ChartSeries](../chartseries)) | 在整个 Collection 中搜索指定的 ChartSeries，并返回其首次出现的零基索引 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | ChartSeries 值。 |

 **返回值：**
int


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert (int, int) | 创建新的图表序列并将其插入到集合中。 |

 **返回值：**
[ChartSeries](../chartseries)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

 **返回值：**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

 **返回值：**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回值：**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ChartSeries](../chartseries)) | 移除指定的值。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | 该值。 |

 **返回值：**
void

 **异常**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | 集合中未找到 value 参数。 |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | 从集合中移除存储在指定位置的 ActiveX 控件。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| index | int | 要移除的控件的索引。 |

 **返回值：**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | 返回集合中对象的数量。只读 int。 |

 **返回值：**
int


---