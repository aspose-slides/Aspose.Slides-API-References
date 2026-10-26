---
title: BehaviorCollection
second_title: Aspose.Slides for Java API 參考
description: 代表行為效果的集合。
type: docs
url: /zh-hant/com.aspose.slides/behaviorcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

代表行為效果的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中行為的數量。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否為唯讀的值。 |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | 將新行為新增到集合中。 |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | 判斷 List 中特定項目的索引。 |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 在指定索引處將新行為插入到集合中。 |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | 將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到陣列，從特定的陣列索引開始。 |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | 從集合中移除指定的行為。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引處從集合中移除行為。 |
| [clear()](#clear--) | 從集合中移除所有行為。 |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的行為。 |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 設定指定索引處的行為。 |
| [iterator()](#iterator--) | 返回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中行為的數量。唯讀 int。

**返回:**  
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否為唯讀的值。唯讀 boolean。

**返回:**  
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 為唯讀則為 true；否則為 false。
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

將新行為新增到集合中。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要新增的行為。 |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

判斷 List 中特定項目的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 List 中定位的物件。 |

**返回:**  
int - 如果在列表中找到項目則返回其索引；否則返回 -1。
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

在指定索引處將新行為插入到集合中。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入新行為的索引位置。 |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要插入的行為。 |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到陣列，從特定的陣列索引開始。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製的元素的目的地一維陣列。該陣列必須使用零基索引。 |
| arrayIndex | int | 複製開始的零基索引。 |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

從集合中移除指定的行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要移除的行為。 |

**返回:**  
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定索引處從集合中移除行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的行為的索引。 |
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

**返回:**  
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到項目則為 true；否則為 false。
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

返回指定索引處的行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要返回的行為的索引。 |

**返回:**  
[IBehavior](../../com.aspose.slides/ibehavior) - 動畫行為。
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

設定指定索引處的行為。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要設定的行為的索引。 |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

返回一個可遍歷集合的列舉器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - 整個集合的 java.util.Iterator。