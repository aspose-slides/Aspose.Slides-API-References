---
title: BehaviorCollection
second_title: Aspose.Slides for Java API 参考
description: 表示行为效果的集合。
type: docs
url: /zh/com.aspose.slides/behaviorcollection/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

表示行为效果的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中行为的数量。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。 |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | 向集合中添加新行为。 |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | 确定 List 中特定项的索引。 |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 在指定索引处向集合中插入新行为。 |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。 |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | 从集合中移除指定的行为。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引处从集合中移除行为。 |
| [clear()](#clear--) | 从集合中移除所有行为。 |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的行为。 |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 在指定索引处设置行为。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中行为的数量。只读 int.

**返回：**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。只读 boolean。

**返回：**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 为只读则为 true；否则为 false。
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

向集合中添加新行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要添加的行为。 |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

确定 List 中特定项目的索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 List 中定位的对象。 |

**返回：**
int - 如果在列表中找到项目，则返回其索引；否则返回 -1。
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

在指定索引处向集合中插入新行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应插入新行为的索引。 |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要插入的行为。 |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | 一维数组，作为从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 复制的元素的目标。数组必须使用从零开始的索引。 |
| arrayIndex | int | 在数组中开始复制的从零开始的索引。 |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

从集合中移除指定的行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要移除的行为。 |

**返回：**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定索引处从集合中移除行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的行为的索引。 |
### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有行为。
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回：**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到项目则为 true；否则为 false。
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

返回指定索引处的行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的行为的索引。 |

**返回：**
[IBehavior](../../com.aspose.slides/ibehavior) - 动画行为。
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

在指定索引处设置行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的行为的索引。 |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - 整个集合的 java.util.Iterator。