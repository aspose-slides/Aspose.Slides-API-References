---
title: PointCollection
second_title: Aspose.Slides for Android via Java API 參考
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
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 傳回集合中點的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回在指定索引處的點。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java iterator。 |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


傳回集合中點的數量。唯讀 int。

**傳回:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


傳回在指定索引處的點。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回:**  
[IPoint](../../com.aspose.slides/ipoint) - 此 [IPoint](../../com.aspose.slides/ipoint) 物件。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


傳回可遍歷集合的列舉器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


傳回整個集合的 java iterator。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - java.util.Iterator 用於整個集合。