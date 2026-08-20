---
title: ColumnCollection
second_title: Aspose.Slides for Java API 參考
description: 表示表格中欄位的集合。
type: docs
url: /zh-hant/com.aspose.slides/columncollection/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**全部已實作介面:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

表示表格中欄位的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中欄位的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的欄位。 |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 建立指定範本列的副本，並將其插入表格底部。 |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 建立指定範本欄的副本，並將其插入表格中指定的位置。 |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 從表格中指定位置移除欄位。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### size() {#size--}
```
public final int size()
```


**傳回:**  
只讀 int.

### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


**傳回:**  
只讀 [Column](../../com.aspose.slides/column).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**  
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


建立指定範本列的副本，並將其插入表格底部。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作範本的欄位。 |
| withAttachedColumns | boolean | 若為 true，亦會複製所有附加於範本列的欄位。 |

**傳回:**  
com.aspose.slides.IColumn[] - 已新增的欄位。
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


建立指定範本欄的副本，並將其插入表格中指定的位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新欄位的索引。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作範本的欄位。 |
| withAttachedColumns | boolean | 若為 true，亦會複製所有附加於範本欄的欄位。 |

**傳回:**  
com.aspose.slides.IColumn[] - 已插入的欄位。
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


從表格中指定位置移除欄位。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| firstColumnIndex | int | 要刪除的欄位索引。 |
| withAttachedRows | boolean | 若為 true，亦會刪除所有附加的欄位。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將所有元素從集合複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回一個值，指示集合的存取是否已同步（執行緒安全）。只讀 boolean.

**傳回:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。只讀 Object.

**傳回:**  
java.lang.Object