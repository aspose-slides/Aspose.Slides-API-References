---
title: LayoutSlideCollection
second_title: Aspose.Slides for Java API 參考
description: 表示布局投影片集合的基底類別。
type: docs
url: /zh-hant/com.aspose.slides/layoutslidecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

表示布局投影片集合的基底類別。

## Methods

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 返回集合中布局投影片的數量。 |
| [get_Item(int index)](#get-Item-int-) | 依索引返回布局投影片。 |
| [getByType(byte type)](#getByType-byte-) | 返回指定類型的第一個布局投影片。 |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | 從集合中移除布局。 |
| [removeUnused()](#removeUnused--) | 移除未使用的布局投影片（HasDependingSlides 為 false 的布局投影片）。 |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 Java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將所有元素從集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

返回集合中布局投影片的數量。唯讀 int。

**傳回:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

依索引返回布局投影片。唯讀 [LayoutSlide](../../com.aspose.slides/layoutslide)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

返回指定類型的第一個布局投影片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | byte | 要尋找的布局投影片類型。 |

**傳回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) 具指定類型，若未找到布局則回傳 null。
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

從集合中移除布局。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要從集合中移除的布局投影片。

--------------------

1) 為避免拋出 PptxEditException，請先檢查布局的 HasDependingSlides 屬性。2) 也可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法簡化程式碼。 |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

移除未使用的布局投影片（HasDependingSlides 為 false 的布局投影片）。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

返回可遍歷集合的列舉器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

返回整個集合的 Java 迭代器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將所有元素從集合複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**傳回:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject