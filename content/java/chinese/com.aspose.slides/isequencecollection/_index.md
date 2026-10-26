---
title: ISequenceCollection
second_title: Aspose.Slides 的 Java API 参考
description: 表示交互序列的集合。
type: docs
url: /zh/com.aspose.slides/isequencecollection/
---
**所有实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

表示交互序列的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中元素的数量 只读 int。 |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 添加新的交互序列。 |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 从集合中删除指定的序列。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的序列。 |
| [clear()](#clear--) | 从集合中删除所有序列。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的序列。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中元素的数量 只读 int。

**返回值:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

添加新的交互序列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape 对象 [IShape](../../com.aspose.slides/ishape) |

**返回值:**
[ISequence](../../com.aspose.slides/isequence) - 新的序列 [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

从集合中删除指定的序列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 要删除的序列。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的序列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中元素的索引 int |

### clear() {#clear--}
```
public abstract void clear()
```

删除集合中的所有序列。

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

返回指定索引处的序列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回值:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) 对象。