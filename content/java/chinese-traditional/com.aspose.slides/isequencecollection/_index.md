---
title: ISequenceCollection
second_title: Aspose.Slides for Java API 參考
description: 表示互動序列的集合。
type: docs
url: /zh-hant/com.aspose.slides/isequencecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

表示互動序列的集合。
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | 傳回集合中元素的數量 唯讀 int。 |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 新增互動序列。 |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 從集合中移除指定的序列。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的序列。 |
| [clear()](#clear--) | 從集合中移除所有序列。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的序列。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


傳回集合中元素的數量 唯讀 int。

**Returns:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


新增互動序列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | 形狀物件 [IShape](../../com.aspose.slides/ishape) |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - 新序列 [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


從集合中移除指定的序列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 要移除的序列。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除指定索引處的序列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 集合中元素的索引 int |

### clear() {#clear--}
```
public abstract void clear()
```


移除集合中所有序列。

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


傳回指定索引處的序列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 索引。 |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - 此 [ISequence](../../com.aspose.slides/isequence) 物件。