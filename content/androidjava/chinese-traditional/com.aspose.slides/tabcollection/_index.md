---
title: TabCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個分頁的集合。
type: docs
url: /zh-hant/com.aspose.slides/tabcollection/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

表示一個分頁的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [add(double position, int align)](#add-double-int-) | 將 Tab 新增到集合中。 |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | 將 Tab 新增到集合中。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷兩個 TabsEx 實例是否相等。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示是否同步（執行緒安全）存取集合的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### size() {#size--}
```
public final int size()
```


取得集合實際包含的元素數量。唯讀 int。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


取得指定索引處的元素。唯讀 [Tab](../../com.aspose.slides/tab)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


將 Tab 新增到集合中。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**返回：**
[ITab](../../com.aspose.slides/itab) - 已新增的 tab。
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


將 Tab 新增到集合中。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | 要在集合末端新增的 Tab 物件。 |

**返回：**
int - Tab 被新增的索引位置。
### clear() {#clear--}
```
public final void clear()
```


從集合中移除所有元素。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除集合中指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素之零基索引。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


判斷兩個 TabsEx 實例是否相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要與目前的 TabsEx 比較的 TabsEx。 |

**返回：**
boolean - **true** 如果指定的 TabsEx 等於目前的 TabsEx；否則，**false**。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


傳回遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


傳回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回指示集合的存取是否同步（執行緒安全）的值。唯讀 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object。

**返回：**
java.lang.Object