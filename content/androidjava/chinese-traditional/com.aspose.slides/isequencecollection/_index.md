---
title: ISequenceCollection
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示互動序列的集合。
type: docs
url: /zh-hant/com.aspose.slides/isequencecollection/
---
**已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

表示互動序列的集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中元素的數量，唯讀 int。 |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 新增互動序列。 |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 從集合中移除指定的序列。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的序列。 |
| [clear()](#clear--) | 從集合中移除所有序列。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的序列。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中元素的數量，唯讀 int。

**返回值：**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

新增互動序列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | 形狀物件 [IShape](../../com.aspose.slides/ishape) |

**返回值：**
[ISequence](../../com.aspose.slides/isequence) - 新的序列 [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

從集合中移除指定的序列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 待移除的序列。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引處的序列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 集合中元素的索引 int |
### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有序列。

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

返回指定索引處的序列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回值：**
[ISequence](../../com.aspose.slides/isequence) - 此 [ISequence](../../com.aspose.slides/isequence) 物件。