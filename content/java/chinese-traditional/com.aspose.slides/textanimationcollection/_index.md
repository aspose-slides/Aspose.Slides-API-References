---
title: TextAnimationCollection
second_title: Aspose.Slides for Java API 參考
description: 表示文字動畫的集合。
type: docs
url: /zh-hant/com.aspose.slides/textanimationcollection/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

表示文字動畫的集合。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中元素的數量。 |
| [add()](#add--) | 新增文字動畫到集合中。 |
| [get_Item(int index)](#get-Item-int-) | 傳回依索引的元素。 |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | 傳回所有元素 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回表示是否同步存取集合（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


傳回集合中元素的數量。唯讀 int.

**傳回:**
int
### add() {#add--}
```
public final TextAnimation add()
```


新增文字動畫到集合中。

**傳回:**
[TextAnimation](../../com.aspose.slides/textanimation) - 已新增 [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


傳回依索引的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


傳回所有元素

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) 以移除。 |

**傳回:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) 的陣列
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


傳回可遍歷集合的列舉器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


傳回整個集合的 java 迭代器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要填充的陣列。 |
| index | int | 目標陣列的開始位置。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回表示是否同步存取集合（執行緒安全）的值。唯讀 boolean。

**傳回:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object。

**傳回:**
java.lang.Object