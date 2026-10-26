---
title: ChartSeriesCollection
second_title: Aspose.Slides for Java API 参考
description: 表示集合
type: docs
url: /zh/com.aspose.slides/chartseriescollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

表示 [ChartSeries](../../com.aspose.slides/chartseries) 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [size()](#size--) | 返回集合中对象的数量。 |
| [add(int type)](#add-int-) | 创建新的图表系列并将其添加到集合中。 |
| [insert(int index, int type)](#insert-int-int-) | 创建新的图表系列并将其插入到集合中。 |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | 从 [ChartDataCell](../../com.aspose.slides/chartdatacell) 创建新的图表系列并将其添加到集合中。 |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | 从 [ChartCellCollection](../../com.aspose.slides/chartcellcollection) 创建新的图表系列并将其添加到集合中。 |
| [add(String name, int type)](#add-java.lang.String-int-) | 从值创建新的图表系列并将其添加到集合中。 |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 搜索指定的 [ChartSeries](../../com.aspose.slides/chartseries)，并返回整个集合中首次出现的从零开始的索引。 |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中移除存储在指定位置的 ActiveX 控件。 |
| [clear()](#clear--) | 从集合中移除所有控件。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将整个集合复制到指定的数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

获取指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 指定索引处的元素。
### size() {#size--}
```
public final int size()
```

返回集合中对象的数量。只读 int。

**返回值：**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 系列类型 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新的图表系列。
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

创建新的图表系列并将其插入到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

从 [ChartDataCell](../../com.aspose.slides/chartdatacell) 创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 包含系列名称的单元格。 |
| type | int | 系列的类型 |

--------------------

如果从同一单元格创建的图表系列已经在集合中，则方法不添加任何内容并返回其索引。 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已添加的图表系列或已在集合中的系列。
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

从 [ChartCellCollection](../../com.aspose.slides/chartcellcollection) 创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 包含系列名称的单元格。 |
| type | int | 系列的类型 |

--------------------

如果从同一单元格创建的图表系列已经在集合中，则方法不添加任何内容并返回其索引。 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已添加的图表系列或已在集合中的系列。
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

从值创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 系列名称。 |
| type | int | 系列的类型 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已添加的图表系列。
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

搜索指定的 [ChartSeries](../../com.aspose.slides/chartseries)，并返回整个集合中首次出现的从零开始的索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 图表系列的值。 |

**返回值：**
int - 如果找到，则返回整个 CollectionBase 中值的首次出现的从零开始的索引；否则返回 -1。
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

移除指定的值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 值。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中移除存储在指定位置的 ActiveX 控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的控件的索引。 |

### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有控件。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

返回一个遍历集合的枚举器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将整个集合复制到指定的数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组 |
| index | int | 目标数组中的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值：**
java.lang.Object