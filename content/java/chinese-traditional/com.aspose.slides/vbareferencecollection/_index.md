---
title: VbaReferenceCollection
second_title: Aspose.Slides for Java API 參考
description: 表示 VBA 專案參考的集合。
type: docs
url: /zh-hant/com.aspose.slides/vbareferencecollection/
---
**繼承:**  
java.lang.Object

**所有實作的介面:**  
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)  
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

表示 VBA 專案參考的集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | 將新參考加入參考集合 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### size() {#size--}
```
public final int size()
```

取得集合實際包含的元素數量。唯讀 int。

**傳回:**  
int
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```

將新參考加入參考集合

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |
### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |
**傳回:**  
[IVbaReference](../../com.aspose.slides/ivbareference)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```

傳回一個可遍歷集合的列舉器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - 可用於遍歷集合的 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - 整個集合的 java.util.Iterator
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean。

**傳回:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回:**  
java.lang.Object