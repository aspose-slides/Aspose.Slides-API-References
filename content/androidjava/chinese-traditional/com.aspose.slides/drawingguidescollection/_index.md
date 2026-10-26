---
title: DrawingGuidesCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表可調整繪圖參考線的集合。
type: docs
url: /zh-hant/com.aspose.slides/drawingguidescollection/
---
**繼承:**
java.lang.Object

**全部已實作的介面:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

代表一個可調整繪圖參考線的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回索引處的繪圖參考線。 |
| [add(byte orientation, float position)](#add-byte-float-) | 在集合末尾加入繪圖參考線。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的繪圖參考線。 |
| [clear()](#clear--) | 移除集合中的全部元素。 |
| [iterator()](#iterator--) | 返回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [getCount()](#getCount--) | 返回集合中元素的數量。 |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | 將集合中的所有元素複製到指定的陣列。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


返回索引處的繪圖參考線。唯讀 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**回傳值:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


在集合末尾加入繪圖參考線。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| orientation | byte | 繪圖參考線的方向。 |
| position | float | 繪圖參考線的座標（以點為單位）。 |

**回傳值:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除指定索引處的繪圖參考線。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 應刪除之繪圖參考線的索引。 |

### clear() {#clear--}
```
public final void clear()
```


移除集合中的所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


返回一個可遍歷集合的列舉器。

**回傳值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


返回整個集合的 java 迭代器。

**回傳值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 整個集合的 java.util.Iterator。

### getCount() {#getCount--}
```
public final int getCount()
```


返回集合中元素的數量。唯讀 int。

**回傳值:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |