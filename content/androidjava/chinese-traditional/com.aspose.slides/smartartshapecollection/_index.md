---
title: SmartArtShapeCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 SmartArt 形狀的集合
type: docs
url: /zh-hant/com.aspose.slides/smartartshapecollection/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

表示 SmartArt 形狀的集合
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [iterator()](#iterator--) | 傳回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```


取得集合中實際包含的元素數量。唯讀 int.

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```


取得指定索引處的元素。唯讀 [SmartArtShape](../../com.aspose.slides/smartartshape)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 形狀的索引 |

**返回：**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt shape
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

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```


傳回一個可遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - 可用於遍歷集合的 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```


傳回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - 整個集合的 java.util.Iterator