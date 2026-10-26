---
title: RowCollection
second_title: Aspose.Slides 用於 Java 的 API 參考
description: 表示表格列集合。
type: docs
url: /zh-hant/com.aspose.slides/rowcollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

表示表格列集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的列數。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的列。 |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 建立指定範本列的副本，並插入到表格底部。 |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 建立指定範本列的副本，並插入到表格的指定位置。 |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 從表格的指定位置移除一列。 |
| [iterator()](#iterator--) | 傳回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 Java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### size() {#size--}
```
public final int size()
```

取得集合中實際包含的列數。唯讀 int.

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

傳回指定索引處的列。唯讀 [Row](../../com.aspose.slides/row)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

建立指定範本列的副本，並插入到表格底部。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | 作為範本使用的列。 |
| withAttachedRows | boolean | True 表示同時複製所有附加於範本列的列。 |

**返回：**
com.aspose.slides.IRow[] - 已新增的列。
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

建立指定範本列的副本，並插入到表格的指定位置。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 新列的索引。 |
| templ | [IRow](../../com.aspose.slides/irow) | 作為範本使用的列。 |
| withAttachedRows | boolean | True 表示同時複製所有附加於範本列的列。 |

**返回：**
com.aspose.slides.IRow[] - 已插入的列。
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

從表格的指定位置移除一列。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| firstRowIndex | int | 要刪除之列的索引。 |
| withAttachedRows | boolean | True 表示同時刪除所有附屬列。 |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

傳回一個可遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

傳回整個集合的 Java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**返回：**
java.lang.Object