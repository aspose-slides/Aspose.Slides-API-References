---
title: DrawingGuidesCollection
second_title: Aspose.Slides Java API 參考
description: 表示可調整的繪圖參考線集合。
type: docs
url: /zh-hant/com.aspose.slides/drawingguidescollection/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

表示一個可調整的繪圖參考線集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引的繪圖參考線。 |
| [add(byte orientation, float position)](#add-byte-float-) | 在集合的尾端新增繪圖參考線。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引的繪圖參考線。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 Java 迭代器。 |
| [getCount()](#getCount--) | 傳回集合中元素的數量。 |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | 將集合中的所有元素複製到指定的陣列。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


傳回指定索引的繪圖參考線。唯讀 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**回傳值：**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


在集合的尾端新增繪圖參考線。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| orientation | byte | 繪圖參考線的方向。 |
| position | float | 繪圖參考線在點數上的位置。 |

**回傳值：**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除指定索引的繪圖參考線。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 應刪除的繪圖參考線索引。 |

### clear() {#clear--}
```
public final void clear()
```


從集合中移除所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


傳回用於遍歷集合的列舉器。

**回傳值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


傳回整個集合的 Java 迭代器。

**回傳值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 整個集合的 java.util.Iterator。
### getCount() {#getCount--}
```
public final int getCount()
```


傳回集合中元素的數量。唯讀 int。

**回傳值：**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |