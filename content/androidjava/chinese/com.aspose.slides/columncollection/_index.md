---
title: ColumnCollection
second_title: Aspose.Slides for Android via Java API 参考
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
| [size()](#size--) | Returns the number of columns in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the column at the specified index. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template column and insert it at the specified position in a table. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a column at the specified position from a table. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```

返回集合中列的数量。只读 int。

**返回值:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

返回指定索引处的列。只读 [Column](../../com.aspose.slides/column)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**  
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

创建指定模板行的副本并将其插入表格底部。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的列。 |
| withAttachedColumns | boolean | True 表示同时复制附加到模板行的所有列。 |

**返回值:**  
com.aspose.slides.IColumn[] - 已添加的列。
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

创建指定模板列的副本并将其插入表格中指定位置。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新列的索引。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的列。 |
| withAttachedColumns | boolean | True 表示同时复制附加到模板列的所有列。 |

**返回值:**  
com.aspose.slides.IColumn[] - 已插入的列。
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

从表格中指定位置移除列。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstColumnIndex | int | 要删除的列的索引。 |
| withAttachedRows | boolean | True 表示同时删除所有附加的列。 |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

返回遍历集合的枚举器。

**返回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 用于遍历整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回值指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回值:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值:**  
java.lang.Object