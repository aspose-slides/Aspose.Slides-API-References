---
title: SectionSlideCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表此區段中的投影片集合。
type: docs
url: /zh-hant/com.aspose.slides/sectionslidecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面：**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

代表此區段中的投影片集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將整個集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

取得指定索引處的元素。唯讀 [ISlide](../../com.aspose.slides/islide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

取得集合實際包含的元素數量。唯讀 int。

**返回：**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將整個集合複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列 |
| index | int | 目標陣列中的索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**返回：**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

傳回可遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

傳回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.