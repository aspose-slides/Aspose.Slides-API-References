---
title: RowCollection
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示表行集合。
type: docs
url: /zh/com.aspose.slides/rowcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

表示表行集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的行数。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的行。 |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 创建指定模板行的副本并将其插入表的底部。 |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 创建指定模板行的副本并将其插入表中的指定位置。 |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 删除表中指定位置的行。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### size() {#size--}
```
public final int size()
```

获取集合中实际包含的行数。只读 int.

**返回:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

返回指定索引处的行。只读 [Row](../../com.aspose.slides/row)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

创建指定模板行的副本并将其插入表的底部。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | 用作模板的行。 |
| withAttachedRows | boolean | 若为 true，则同时复制所有附加到模板行的行。 |

**返回:**  
com.aspose.slides.IRow[] - 已添加的行。

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

创建指定模板行的副本并将其插入表中的指定位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新行的索引。 |
| templ | [IRow](../../com.aspose.slides/irow) | 用作模板的行。 |
| withAttachedRows | boolean | 若为 true，则同时复制所有附加到模板行的行。 |

**返回:**  
com.aspose.slides.IRow[] - 已插入的行。

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

从表中删除指定位置的行。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstRowIndex | int | 要删除的行的索引。 |
| withAttachedRows | boolean | 若为 true，则同时删除所有附加的行。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

返回一个遍历集合的枚举器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - An java.util.Iterator for the entire collection.

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

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回:**  
java.lang.Object