---
title: BehaviorCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表行為效果的集合。
type: docs
url: /zh-hant/com.aspose.slides/behaviorcollection/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

代表行為效果的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中行為的數量。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否為唯讀的值。 |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | 將新行為加入集合。 |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | 確定 List 中特定項目的索引。 |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 在指定索引處將新行為插入集合。 |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | 複製 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素到陣列，從特定的陣列索引開始。 |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | 從集合中移除指定的行為。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引處從集合中移除行為。 |
| [clear()](#clear--) | 從集合中移除所有行為。 |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [get_Item(int index)](#get-Item-int-) | 在指定索引處傳回行為。 |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 在指定索引處設定行為。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中行為的數量。唯讀 int.

**傳回值:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否為唯讀的值。唯讀 boolean.

**傳回值:**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 為唯讀則為 true；否則為 false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

將新行為加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要新增的行為。 |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

確定 List 中特定項目的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 List 中定位的物件。 |

**傳回值:**
int - 若在清單中找到 item，則傳回其索引；否則傳回 -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

在指定索引處將新行為插入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要在集合中插入新行為的索引位置。 |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要插入的行為。 |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到陣列，從特定的陣列索引開始。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製的元素之目的地的一維陣列。該陣列必須使用零基索引。 |
| arrayIndex | int | 複製開始時陣列中的零基索引。 |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

從集合中移除指定的行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要移除的行為。 |

**傳回值:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定索引處從集合中移除行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之行為的索引。 |
### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有行為。
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**傳回值:**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 則為 true；否則為 false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

在指定索引處傳回行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要傳回之行為的索引。 |

**傳回值:**
[IBehavior](../../com.aspose.slides/ibehavior) - 動畫行為。
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

在指定索引處設定行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要設定之行為的索引。 |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

傳回遍歷集合的列舉器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - An java.util.Iterator for the entire collection.