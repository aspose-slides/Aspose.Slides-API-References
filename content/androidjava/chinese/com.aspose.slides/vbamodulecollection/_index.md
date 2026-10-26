---
title: VbaModuleCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 VBA 项目模块的集合。
type: docs
url: /zh/com.aspose.slides/vbamodulecollection/
---
**继承:**
java.lang.Object

**所有已实现的接口:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

表示 VBA 项目模块的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合实际包含的元素数量。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | 从集合中移除特定对象的第一次出现。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | 向 VBA 项目添加一个新的空模块。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

获取集合实际包含的元素数量。只读 int。

**返回:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

从集合中移除特定对象的第一次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | 要从集合中移除的模块。 |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

向 VBA 项目添加一个新的空模块。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 模块的名称 |

**返回:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 已添加的模块。
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

返回遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 整个集合的 java.util.Iterator。
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