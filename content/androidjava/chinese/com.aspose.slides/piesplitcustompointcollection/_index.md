---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示在条形饼图或饼中饼图中使用自定义拆分的拆分点的点集合。
type: docs
url: /zh/com.aspose.slides/piesplitcustompointcollection/
---
**继承:**
java.lang.Object

**所有已实现的接口:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

表示在条形饼图或饼中饼图中用于自定义拆分点的点集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的图表数据点。 |
| [add(int dataPointIndex)](#add-int-) | 通过其在父系列点集合中的索引添加数据点。 |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | 向集合中添加数据点。 |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | 从集合中移除项目。 |
| [remove(int dataPointIndex)](#remove-int-) | 通过其在父系列点集合中的索引从集合中移除项目。 |
| [clear()](#clear--) | 从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除所有项目。 |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。 |
| [size()](#size--) | 获取或设置图表数据点的计数。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根对象。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

返回指定索引处的图表数据点。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 图表数据点。

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

通过其在父系列点集合中的索引添加数据点。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父系列点集合中数据点的索引。 |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

向集合中添加数据点。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 添加到的数据点。 |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

从集合中移除项目。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 移除的目标数据点。 |

**返回值:**
boolean - 如果成功移除项目则为 true；否则为 false。如果在 System.Collections.Generic.List{T} 中未找到项目，此方法也返回 false。

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

通过其在父系列点集合中的索引从集合中移除项目。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父系列点集合中数据点的索引。 |

### clear() {#clear--}
```
public final void clear()
```

从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除所有项目。

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回值:**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到项则为 true；否则为 false。

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | 接收从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 复制的元素的一维数组。数组必须使用零基索引。 |
| arrayIndex | int | 复制开始的零基数组索引。 |

### size() {#size--}
```
public final int size()
```

获取或设置图表数据点的计数。只读 int。

**返回值:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。只读 boolean。

**返回值:**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 为只读则为 true；否则为 false。

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回值:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根对象。只读 Object。

**返回值:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

返回一个遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 整个集合的 java.util.Iterator。