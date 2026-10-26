---
title: ColumnCollection
second_title: Aspose.Slides for Java API 参考
description: 表示表格中列的集合。
type: docs
url: /zh/com.aspose.slides/columncollection/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有已实现的接口:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

表示表格中列的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中列的数量。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的列。 |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 创建指定模板行的副本并将其插入表格的底部。 |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 创建指定模板列的副本并将其插入表格的指定位置。 |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 从表格的指定位置删除列。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

返回集合中列的数量。只读 int.

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

返回指定索引处的列。只读 [Column](../../com.aspose.slides/column)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

创建指定模板行的副本并将其插入表格的底部。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的列。 |
| withAttachedColumns | boolean | 若为 true，则还复制所有附加到模板行的列。 |

**返回：**
com.aspose.slides.IColumn[] - 已添加的列。
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

创建指定模板列的副本并将其插入表格的指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新列的索引。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的列。 |
| withAttachedColumns | boolean | 若为 true，则还复制所有附加到模板列的列。 |

**返回：**
com.aspose.slides.IColumn[] - 已插入的列。
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

从表格的指定位置删除列。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstColumnIndex | int | 要删除的列的索引。 |
| withAttachedRows | boolean | 若为 true，则也删除所有附加的列。 |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回：**
java.lang.Object