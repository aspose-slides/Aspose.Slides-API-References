---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變物件，表示有效影像轉換效果之唯讀集合。
type: docs
url: /zh-hant/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

不可變物件，表示有效影像轉換效果之唯讀集合。

--------------------

Name IImageTransformOperationCollectionEffectiveData truncuted to IImageTransformOCollectionEffectiveData because of COM names length cannot be more then 39.

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中影像效果的數量。 |
| [get_Item(int index)](#get-Item-int-) | 依索引傳回元素。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的物件是否等於目前的物件。 |
| [hashCode()](#hashCode--) | 為特定類型提供雜湊函式，適用於雜湊演算法與資料結構，如雜湊表。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉子。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示是否同步存取集合 (執行緒安全) 的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |

### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```

### size() {#size--}
```
public final int size()
```

傳回集合中影像效果的數量。唯讀 int。

**傳回值：**
int

### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```

依索引傳回元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回值：**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - The [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) object.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的物件是否等於目前的物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要與目前物件比較的物件。 |

**傳回值：**
boolean - true if the specified object is equal to the current object; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

為特定類型提供雜湊函式，適用於雜湊演算法與資料結構，如雜湊表。

**傳回值：**
int - A hash code for the current object.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```

傳回可遍歷集合的列舉子。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要填充的陣列。 |
| index | int | 目標陣列的起始位置。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示是否同步存取集合 (執行緒安全) 的值。唯讀 boolean。

**傳回值：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值：**
java.lang.Object