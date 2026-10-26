---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides for Java API 参考
description: 表示用于在条形饼图或嵌套饼图中进行自定义拆分的拆分点集合。
type: docs
url: /zh/com.aspose.slides/piesplitcustompointcollection/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

表示用于在条形饼图或嵌套饼图中进行自定义拆分的拆分点集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的图表数据点。 |
| [add(int dataPointIndex)](#add-int-) | 通过在父系列点集合中的索引添加数据点。 |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | 将数据点添加到集合中。 |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | 从集合中移除项。 |
| [remove(int dataPointIndex)](#remove-int-) | 通过在父系列点集合中的索引从集合中移除项。 |
| [clear()](#clear--) | 从[IGenericCollection](../../com.aspose.slides/igenericcollection)中移除所有项。 |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | 确定[IGenericCollection](../../com.aspose.slides/igenericcollection)是否包含特定值。 |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | 将[IGenericCollection](../../com.aspose.slides/igenericcollection)的元素复制到数组中，起始于特定的数组索引。 |
| [size()](#size--) | 返回或设置图表数据点的计数。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示[IGenericCollection](../../com.aspose.slides/igenericcollection)是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回一个枚举器，用于遍历集合。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

返回指定索引的图表数据点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 图表数据点。

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

通过在父系列点集合中的索引添加数据点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父系列点集合中数据点的索引。 |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

将数据点添加到集合。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 要添加的数据点。 |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

从集合中移除项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 要移除的数据点。 |

**返回：**
boolean - 如果成功移除项则为 true；否则为 false。如果在 System.Collections.Generic.List\{T\} 中未找到该项，也返回 false。

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

通过在父系列点集合中的索引从集合中移除项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父系列点集合中数据点的索引。 |

### clear() {#clear--}
```
public final void clear()
```

从[IGenericCollection](../../com.aspose.slides/igenericcollection)中移除所有项。

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

确定[IGenericCollection](../../com.aspose.slides/igenericcollection)是否包含特定值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 要在[IGenericCollection](../../com.aspose.slides/igenericcollection)中定位的对象。 |

**返回：**
boolean - 如果在[IGenericCollection](../../com.aspose.slides/igenericcollection)中找到该项则为 true；否则为 false。

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

将[IGenericCollection](../../com.aspose.slides/igenericcollection)的元素复制到数组中，起始于特定的数组索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | 目标是一维数组，用于接收从[IGenericCollection](../../com.aspose.slides/igenericcollection)复制的元素。数组必须使用零基索引。 |
| arrayIndex | int | 复制开始的零基数组索引。 |

### size() {#size--}
```
public final int size()
```

返回或设置图表数据点的计数。只读 int。

**返回：**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示[IGenericCollection](../../com.aspose.slides/igenericcollection)是否为只读。只读 boolean。

**返回：**
boolean - 如果[IGenericCollection](../../com.aspose.slides/igenericcollection)为只读则为 true；否则为 false。

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回：**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

返回一个枚举器，用于遍历集合。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 用于整个集合的 java.util.Iterator。