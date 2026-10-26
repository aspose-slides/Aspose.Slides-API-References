---
title: TabCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 Tab 集合。
type: docs
url: /zh/com.aspose.slides/tabcollection/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

表示一个 Tab 集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [add(double position, int align)](#add-double-int-) | 将 Tab 添加到集合中。 |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | 将 Tab 添加到集合中。 |
| [clear()](#clear--) | 删除集合中的所有元素。 |
| [removeAt(int index)](#removeAt-int-) | 删除集合中指定索引处的元素。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个 TabsEx 实例是否相等。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组中。 |
| [isSynchronized()](#isSynchronized--) | 返回指示对集合的访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根对象。 |
### size() {#size--}
```
public final int size()
```

获取集合中实际包含的元素数量。只读 int。

**返回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

获取指定索引处的元素。只读 [Tab](../../com.aspose.slides/tab)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

将 Tab 添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**返回值：**
[ITab](../../com.aspose.slides/itab) - 已添加的 Tab。
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

将 Tab 添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | 要添加到集合末尾的 Tab 对象。 |

**返回值：**
int - Tab 添加所在的索引。
### clear() {#clear--}
```
public final void clear()
```

删除集合中的所有元素。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

删除集合中指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的元素的零基索引。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定两个 TabsEx 实例是否相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与当前 TabsEx 比较的 TabsEx。 |

**返回值：**
boolean - **true** 如果指定的 TabsEx 等于当前 TabsEx；否则为 **false**。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

返回一个遍历集合的枚举器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - 用于整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回指示对集合的访问是否同步（线程安全）的值。只读 boolean。

**返回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根对象。只读 Object。

**返回值：**
java.lang.Object