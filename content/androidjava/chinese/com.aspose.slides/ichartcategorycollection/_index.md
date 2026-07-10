---
title: IChartCategoryCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示集合
type: docs
url: /zh/com.aspose.slides/ichartcategorycollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

表示 [IChartCategory](../../com.aspose.slides/ichartcategory) 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getUseCells()](#getUseCells--) | 如果为 true，则工作表用于存储类别（此情况支持多级类别）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | 如果为 true，则工作表用于存储类别（此情况支持多级类别）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 返回使用的类别分组层级计数。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 如果集合中已存在该类别，则返回它。 |
| [add(Object value)](#add-java.lang.Object-) | 从值创建新的 [IChartCategory](../../com.aspose.slides/ichartcategory) 并添加到集合中。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 搜索指定的 [IChartCategory](../../com.aspose.slides/ichartcategory)，返回整个集合中第一次出现的零基索引。 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除给定索引处的元素。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定索引处的元素。
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

如果为 true，则工作表用于存储类别（此情况支持多级类别）。如果为 false，则工作表不用于存储值（此情况不支持多级类别）。读写布尔值。

**返回:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

如果为 true，则工作表用于存储类别（此情况支持多级类别）。如果为 false，则工作表不用于存储值（此情况不支持多级类别）。读写布尔值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

返回使用的类别分组层级计数。多级类别时大于 1。只读 int。

**返回:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

如果集合中已存在该类别，则返回它。否则从 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 创建新的图表类别并将其添加到集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 用于创建图表类别的单元格。 |

**返回:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已添加的或已有的类别。
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

从值创建新的 [IChartCategory](../../com.aspose.slides/ichartcategory) 并将其添加到集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 该值。 |

--------------------

此方法会创建名称为 AUTO_DATA 的工作表并将所有值添加到该工作表。如果使用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) 添加或编辑单元格值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。

**返回:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已添加的 [IChartCategory](../../com.aspose.slides/ichartcategory)。
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

搜索指定的 [IChartCategory](../../com.aspose.slides/ichartcategory)，返回整个集合中第一次出现的零基索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 图表类别。 |

**返回:**
int - 值在整个 CollectionBase 中首次出现的零基索引，如果找到；否则为 -1。
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

移除指定的值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 该值。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除给定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的类别的索引。 |
### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有元素。