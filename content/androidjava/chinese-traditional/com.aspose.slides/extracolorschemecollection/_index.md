---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示一個附加色彩配置的集合。
type: docs
url: /zh-hant/com.aspose.slides/extracolorschemecollection/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

表示一個附加色彩配置的集合。
## Methods

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中元素的數量。 |
| [get_Item(int index)](#get-Item-int-) | 依索引傳回色彩配置。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對 ArrayList 的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回可用於同步存取集合的物件。 |
### size() {#size--}
```
public final int size()
```

傳回集合中元素的數量。唯讀 int。

**傳回:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

依索引傳回色彩配置。唯讀 [ExtraColorScheme](../../com.aspose.slides/extracolorscheme)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

傳回可遍歷集合的列舉器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 陣列中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對 ArrayList 的存取是否已同步（執行緒安全）。唯讀 boolean。

**傳回:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回可用於同步存取集合的物件。唯讀 Object。

傳回同步根。唯讀 Object。

**傳回:**
java.lang.Object