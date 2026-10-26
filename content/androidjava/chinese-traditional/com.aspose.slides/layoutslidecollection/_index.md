---
title: LayoutSlideCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示版面投影片集合的基礎類別。
type: docs
url: /zh-hant/com.aspose.slides/layoutslidecollection/
---
**繼承:**  
java.lang.Object

**所有已實作介面:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject  
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

表示版面投影片集合的基礎類別。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中版面投影片的數量。 |
| [get_Item(int index)](#get-Item-int-) | 根據索引返回版面投影片。 |
| [getByType(byte type)](#getByType-byte-) | 返回指定類型的第一個版面投影片。 |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | 從集合中移除版面。 |
| [removeUnused()](#removeUnused--) | 移除未使用的版面投影片（其 HasDependingSlides 為 false 的版面投影片）。 |
| [iterator()](#iterator--) | 返回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，用於指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

返回集合中版面投影片的數量。唯讀 int。

**返回:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

根據索引返回版面投影片。唯讀 [LayoutSlide](../../com.aspose.slides/layoutslide)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

返回指定類型的第一個版面投影片。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| type | byte | 要查找的版面投影片類型。 |

**返回:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) 具有指定類型的版面投影片，若未找到則為 null。

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

從集合中移除版面。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要從集合中移除的版面投影片。 |
--------------------
1) 為避免拋出 PptxEditException，請先檢查版面的 HasDependingSlides 屬性。 2) 您也可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法來簡化程式碼。 |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

移除未使用的版面投影片（其 HasDependingSlides 為 false 的版面投影片）。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

返回遍歷集合的列舉器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 整個集合的 java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，用於指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean。

**返回:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**返回:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject