---
title: CellCollection
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 表示儲存格的集合。
type: docs
url: /zh-hant/com.aspose.slides/cellcollection/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject  
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

表示一個儲存格集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | 返回集合中儲存格的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回位於指定位置的儲存格。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [getSlide()](#getSlide--) | 傳回 CellCollection 的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 CellCollection 的父簡報。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject

### size() {#size--}
```
public final int size()
```

傳回集合中儲存格的數量。唯讀 int。

**返回:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

傳回位於指定位置的儲存格。唯讀 [Cell](../../com.aspose.slides/cell)。

--------------------

如果儲存格已合併，則一個 Cell 物件可能會對多個索引返回。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[ICell](../../com.aspose.slides/icell)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

傳回用於遍歷集合的列舉器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

傳回整個集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - 整個集合的 java.util.Iterator。

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 CellCollection 的父投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 CellCollection 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**返回:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**返回:**  
java.lang.Object