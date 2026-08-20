---
title: SequenceCollection
second_title: Aspose.Slides for Java API 參考
description: 表示互動序列的集合。
type: docs
url: /zh-hant/com.aspose.slides/sequencecollection/
---
**Inheritance:**  
繼承：

java.lang.Object

**All Implemented Interfaces:**  
全部已實作的介面：

[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

表示互動序列的集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中元素的數量 唯讀 int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 新增互動序列. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | 從集合中移除指定的序列. |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的序列. |
| [clear()](#clear--) | 從集合中移除所有序列. |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的序列. |
| [iterator()](#iterator--) | 返回一個列舉器，用於遍歷集合. |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器. |

### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中元素的數量 唯讀 int.

**回傳：**  
int

### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

新增互動序列. 讀寫 [Sequence](../../com.aspose.slides/sequence).

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**回傳：**  
[ISequence](../../com.aspose.slides/isequence)

### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

從集合中移除指定的序列.

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 要移除的序列. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引處的序列.

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 應刪除的序列之索引. |

### clear() {#clear--}
```
public final void clear()
```

移除集合中所有序列.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

返回指定索引處的序列.

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引. |

**回傳：**  
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) 物件.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

返回一個列舉器，用於遍歷集合.

**回傳：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 一個可用於遍歷集合的 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

返回整個集合的 java 迭代器.

**回傳：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - 一個 java.util.Iterator，用於遍歷整個集合.