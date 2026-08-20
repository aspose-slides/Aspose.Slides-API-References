---
title: FillFormatCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示填充樣式的集合。
type: docs
url: /zh-hant/com.aspose.slides/fillformatcollection/
---
**繼承:** 
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面:** 
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
```
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

表示填充樣式的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [size()](#size--) | 取得實際包含於集合中的元素數量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回表示集合的存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

取得指定索引處的元素。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

傳回用於遍歷集合的列舉器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - java.util.Iterator，用於遍歷整個集合。
### size() {#size--}
```
public final int size()
```

取得實際包含於集合中的元素數量。唯讀 int。

**傳回值:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回表示集合的存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回值:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值:**
java.lang.Object