---
title: PieSplitCustomPointCollection
second_title: 适用于 PHP 的 Aspose.Sildes via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/piesplitcustompointcollection/
---
## PieSplitCustomPointCollection 类

 表示在条形饼图或饼形饼图中使用自定义分割的拆分点集合。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (int) | 通过其在父系列点集合中的索引添加数据点。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父系列点集合中数据点的索引。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 未找到具有给定索引的点。 |


---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([ChartDataPoint](../chartdatapoint)) | 向集合中添加数据点。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | 要添加的数据点。 |

 **返回值：**
void


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从 IGenericCollection 中移除所有项目。 |

 **返回值：**
void


---


### containsItem {#containsItem}

| 名称 | 描述 |
| --- | --- |
| containsItem ([ChartDataPoint](../chartdatapoint)) | 确定 IGenericCollection 是否包含特定值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [ChartDataPoint](../chartdatapoint) | 要在 IGenericCollection 中定位的对象。 |

 **返回值：**
boolean


---


### copyToTArray {#copyToTArray}

| 名称 | 描述 |
| --- | --- |
| copyToTArray (com.aspose.slides.IChartDataPoint[], int) | 将 IGenericCollection 的元素复制到数组中，从特定的数组索引开始。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.slides.IChartDataPoint[] | 一维数组，作为从 IGenericCollection 复制的元素的目标。数组必须使用零基索引。 |
| arrayIndex | int | 在数组中复制开始的零基索引。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | 源 IGenericCollection 中的元素数量大于从 arrayIndex 到目标数组末尾的可用空间。 |


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读对象。 |

 **返回值：**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回指定索引的图表数据点。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

 **返回值：**
[ChartDataPoint](../chartdatapoint)


---


### isReadOnly {#isReadOnly}

| 名称 | 描述 |
| --- | --- |
| isReadOnly () | 获取一个值，指示 IGenericCollection 是否只读。只读布尔值。 |

 **返回值：**
boolean


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读布尔值。 |

 **返回值：**
boolean


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
| iteratorJava () | 返回整个集合的 Java 迭代器。 |

 **返回值：**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove (int) | 通过其在父系列点集合中的索引从集合中移除项目。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父系列点集合中数据点的索引。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | dataPointIndex 为负数。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([ChartDataPoint](../chartdatapoint)) | 从集合中移除项目。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | 要移除的数据点。 |

 **返回值：**
boolean


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回或设置图表数据点的计数。只读整数。 |

 **返回值：**
int


---