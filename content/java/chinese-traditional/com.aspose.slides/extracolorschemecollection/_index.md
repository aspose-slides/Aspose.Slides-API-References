---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides for Java API 參考
description: 表示一個額外色彩配置的集合。
type: docs
url: /zh-hant/com.aspose.slides/extracolorschemecollection/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

表示一個額外色彩配置的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 返回集合中元素的數量。 |
| [get_Item(int index)](#get-Item-int-) | 返回索引處的顏色方案。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指示對 ArrayList 的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回一個可用於同步存取集合的物件。 |
### size() {#size--}
```
public final int size()
```

返回集合中元素的數量。唯讀 int。

**返回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

返回索引處的顏色方案。唯讀 [ExtraColorScheme](../../com.aspose.slides/extracolorscheme)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

返回可遍歷集合的列舉器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - 一個可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 陣列中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，指示對 ArrayList 的存取是否已同步（執行緒安全）。唯讀 boolean。

**返回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回一個可用於同步存取集合的物件。唯讀 Object。

返回同步根。唯讀 Object。

**返回值：**
java.lang.Object