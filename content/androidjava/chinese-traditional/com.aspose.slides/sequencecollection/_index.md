---
title: SequenceCollection
second_title: Aspose.Slides for Android 之 Java API 參考
description: 代表互動序列的集合。
type: docs
url: /zh-hant/com.aspose.slides/sequencecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

代表互動序列的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 傳回集合中元素的數量，只讀 int。 |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 新增互動序列。 |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 從集合中移除指定的序列。 |
| [removeAt(int index)](#removeAt-int-) | 在指定的索引處移除序列。 |
| [clear()](#clear--) | 從集合中移除所有序列。 |
| [get_Item(int index)](#get-Item-int-) | 傳回在指定索引處的序列。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### getCount() {#getCount--}
```
public final int getCount()
```

傳回集合中元素的數量，只讀 int。

**回傳：**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

新增互動序列。讀寫 [Sequence](../../com.aspose.slides/sequence)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**回傳：**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

從集合中移除指定的序列。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 要移除的序列。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定的索引處移除序列。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 應刪除的序列索引。 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有序列。

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

傳回在指定索引處的序列。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**回傳：**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) 物件。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

傳回可遍歷集合的列舉器。

**回傳：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

傳回整個集合的 java 迭代器。

**回傳：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 用於遍歷整個集合的 java.util.Iterator。