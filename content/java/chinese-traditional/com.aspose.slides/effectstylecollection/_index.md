---
title: EffectStyleCollection
second_title: Aspose.Slides for Java API 參考
description: 表示效果樣式的集合。
type: docs
url: /zh-hant/com.aspose.slides/effectstylecollection/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**全部已實作的介面:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

表示效果樣式的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定位置的元素。 |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [size()](#size--) | 返回集合中元素的數量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將所有元素從集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指示對集合的存取是否同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

返回指定位置的元素。唯讀 [EffectStyle](../../com.aspose.slides/effectstyle)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的位置。 |

**傳回：**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - 指定位置的元素。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

返回可遍歷集合的列舉器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

返回整個集合的 java 迭代器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - 用於整個集合的 java.util.Iterator。
### size() {#size--}
```
public final int size()
```

返回集合中元素的數量。唯讀 int, 唯讀 int。

**傳回：**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將所有元素從集合複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，指示對集合的存取是否同步（執行緒安全）。唯讀 boolean。

**傳回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**傳回：**
java.lang.Object