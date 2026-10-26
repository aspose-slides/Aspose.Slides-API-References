---
title: FillFormatCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示填滿樣式的集合。
type: docs
url: /zh-hant/com.aspose.slides/fillformatcollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**  
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)  
```
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

表示填滿樣式的集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回一個列舉器，用於遍歷集合。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [size()](#size--) | 取得集合中實際包含的元素數目。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將所有元素從集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
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

傳回一個列舉器，用於遍歷集合。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - 用於整個集合的 java.util.Iterator。

### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數目。唯讀 int。

**傳回值:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將所有元素從集合複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回值:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值:**
java.lang.Object