---
title: LineFormatCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示線條樣式的集合。
type: docs
url: /zh-hant/com.aspose.slides/lineformatcollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**全部已實作的介面：**
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

表示線條樣式的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步 (執行緒安全) 的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```


取得指定索引處的元素。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```


傳回用於遍歷集合的列舉器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```


傳回整個集合的 java 迭代器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```


取得集合實際包含的元素數量。唯讀 int。

**傳回：**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回指示集合存取是否同步 (執行緒安全) 的值。唯讀 boolean。

**傳回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object。

**傳回：**
java.lang.Object