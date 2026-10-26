---
title: CellCollection
second_title: Aspose.Slides for Java API 參考
description: 表示儲存格的集合。
type: docs
url: /zh-hant/com.aspose.slides/cellcollection/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

表示儲存格的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | 傳回集合中儲存格的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回依位置取得的 Cell。 |
| [iterator()](#iterator--) | 傳回遍歷集合的 enumerator。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java iterator。 |
| [getSlide()](#getSlide--) | 傳回 CellCollection 的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 CellCollection 的父簡報。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳：**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


傳回集合中儲存格的數量。唯讀 int。

**回傳：**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


傳回依位置取得的 Cell。唯讀 [Cell](../../com.aspose.slides/cell)。

--------------------

若儲存格已合併，單一 Cell 物件可能對多個索引返回。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | int |  |

**回傳：**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


傳回遍歷集合的 enumerator。

**回傳：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


傳回整個集合的 java iterator。

**回傳：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - 用於整個集合的 java.util.Iterator。
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


傳回 CellCollection 的父投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**回傳：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


傳回 CellCollection 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**回傳：**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中所有元素複製到指定的陣列。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回一個值，指示對集合的存取是否同步（執行緒安全）。唯讀 boolean。

**回傳：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object。

**回傳：**
java.lang.Object