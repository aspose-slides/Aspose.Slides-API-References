---
title: SequenceCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示交互式序列的集合。
type: docs
url: /zh/com.aspose.slides/sequencecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

表示交互式序列的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中元素的数量 只读 int。 |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 添加新的交互式序列。 |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 从集合中删除指定的序列。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的序列。 |
| [clear()](#clear--) | 从集合中删除所有序列。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的序列。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### getCount() {#getCount--}
```
public final int getCount()
```


返回集合中元素的数量 只读 int。

**返回：**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


添加新的交互式序列。读写 [Sequence](../../com.aspose.slides/sequence)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**返回：**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


从集合中删除指定的序列。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 要删除的序列。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


删除指定索引处的序列。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的序列的索引。 |

### clear() {#clear--}
```
public final void clear()
```


从集合中删除所有序列。

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


返回指定索引处的序列。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[ISequence](../../com.aspose.slides/isequence) - 该 [ISequence](../../com.aspose.slides/isequence) 对象。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 整个集合的 java.util.Iterator。