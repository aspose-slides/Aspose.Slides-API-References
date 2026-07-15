---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 GradientStopData 物件的集合。
type: docs
url: /zh-hant/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Inheritance:**  
繼承：  
java.lang.Object

**All Implemented Interfaces:**  
所有已實作的介面：  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

表示 GradientStopData 物件的集合。

## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | 返回集合中漸層停止點的數量。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的漸層停止點。 |
| [iterator()](#iterator--) | 返回一個遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指出對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### size() {#size--}
```
public final int size()
```

返回集合中漸層停止點的數量。只讀 int。

**Returns:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

返回指定索引的漸層停止點。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

返回一個遍歷集合的列舉器。

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

返回整個集合的 java 迭代器。

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，指出對集合的存取是否已同步（執行緒安全）。只讀 boolean。

**Returns:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只讀 Object。

**Returns:**  
java.lang.Object