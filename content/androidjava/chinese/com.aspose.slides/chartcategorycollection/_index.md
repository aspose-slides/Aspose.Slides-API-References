---
title: ChartCategoryCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示集合
type: docs
url: /zh/com.aspose.slides/chartcategorycollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)  
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

表示 [ChartCategory](../../com.aspose.slides/chartcategory) 的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getUseCells()](#getUseCells--) | 如果为 true，则工作表用于存储类别（此情况下支持多层类别）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | 如果为 true，则工作表用于存储类别（此情况下支持多层类别）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 返回使用的类别分组级别计数。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 如果集合中存在该类别，则返回它。 |
| [add(Object value)](#add-java.lang.Object-) | 从值创建新的 [ChartCategory](../../com.aspose.slides/chartcategory) 并将其添加到集合中。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 在整个 Collection 中搜索指定的 [ChartCategory](../../com.aspose.slides/chartcategory)，并返回首次出现的零基索引。 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除给定索引处的元素。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [size()](#size--) | 返回集合中元素的数量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对 List 的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回一个可用于同步访问集合的对象。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

获取指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定索引处的元素。

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

如果为 true，则工作表用于存储类别（此情况下支持多层类别）。如果为 false，则工作表不用于存储值（此情况下不支持多层类别）。读/写 boolean。

**返回：**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

如果为 true，则工作表用于存储类别（此情况下支持多层类别）。如果为 false，则工作表不用于存储值（此情况下不支持多层类别）。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

返回使用的类别分组级别计数。对于多层类别，此值大于 1。只读 int。

**返回：**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

如果集合中已存在该类别，则返回它。否则从 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 创建新的图表类别并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 用于创建图表类别的 Cell。 |

**返回：**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已添加或已存在的类别。

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

从值创建新的 [ChartCategory](../../com.aspose.slides/chartcategory) 并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 值。 |

--------------------

此方法会添加名为 AUTO_DATA 的工作表并将所有值添加到该工作表。如果使用 [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) 添加或编辑单元格值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。

**返回：**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已添加的 [IChartCategory](../../com.aspose.slides/ichartcategory)。

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

在整个 Collection 中搜索指定的 [ChartCategory](../../com.aspose.slides/chartcategory)，并返回首次出现的零基索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 图表类别。 |

**返回：**
int - 如果找到，则返回该值在整个 CollectionBase 中首次出现的零基索引；否则返回 -1。

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

移除指定的值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 值。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除给定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的类别的索引。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - 用于整个集合的 java.util.Iterator。

### size() {#size--}
```
public final int size()
```

返回集合中元素的数量。只读 int。

**返回：**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合的所有元素复制到指定数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对 List 的访问是否已同步（线程安全）。只读 boolean。

**返回：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回一个可用于同步访问集合的对象。只读 Object。

返回同步根。只读 Object。

**返回：**
java.lang.Object