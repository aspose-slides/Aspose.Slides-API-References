---
title: PointCollection
second_title: Aspose.Slides for Java API 參考
description: 表示動畫點的集合。
type: docs
url: /zh-hant/com.aspose.slides/pointcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

表示動畫點的集合。
## Constructors

| Constructor | Description |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | 傳回集合中點的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的點。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


傳回集合中點的數量。唯讀 int。

**Returns:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


傳回指定索引處的點。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 元素的索引。 |

**Returns:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) 物件。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


傳回可遍歷集合的列舉器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


傳回整個集合的 java 迭代器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - 用於遍歷整個集合的 java.util.Iterator。