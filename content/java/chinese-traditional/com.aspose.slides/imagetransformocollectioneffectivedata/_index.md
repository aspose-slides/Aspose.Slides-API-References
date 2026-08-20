---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變物件，代表只讀的有效影像變換效果集合。
type: docs
url: /zh-hant/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**繼承:**  
java.lang.Object

**所有已實作介面:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)  
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

表示只讀有效影像變換效果集合的不可變物件。

--------------------

名稱 IImageTransformOperationCollectionEffectiveData 被截斷為 IImageTransformOCollectionEffectiveData，因為 COM 名稱長度不能超過 39 個字元。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中影像效果的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回索引位置的元素。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的物件是否等於目前的物件。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式，可用於雜湊演算法與類似雜湊表的資料結構。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列中。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```

### size() {#size--}
```
public final int size()
```

傳回集合中影像效果的數量。唯讀 int.

**傳回值:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```

傳回索引位置的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回值:**  
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - 該 [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) 物件。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的物件是否等於目前的物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要與目前物件比較的物件。 |

**傳回值:**  
boolean - 若指定的物件等於目前的物件則為 true；否則為 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式，可用於雜湊演算法與類似雜湊表的資料結構。

**傳回值:**  
int - 目前物件的雜湊碼。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```

傳回可遍歷集合的列舉器。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - 用於整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列中。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要填充的陣列。 |
| index | int | 目標陣列的起始位置。 |

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