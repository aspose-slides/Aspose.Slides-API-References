---
title: ColumnCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示表格中列的集合。
type: docs
url: /zh-hant/com.aspose.slides/columncollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已實作介面:**  
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)  
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

表示表格中列的集合。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 返回集合中的列數。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的列。 |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 建立指定模板 row 的副本，並將其插入表格底部。 |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 建立指定模板 column 的副本，並將其插入表格的指定位置。 |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 移除表格中指定位置的 column。 |
| [iterator()](#iterator--) | 返回用於遍歷集合的 enumerator。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java iterator。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的 array。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指示對集合的存取是否同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

返回集合中的列數。唯讀 int。

**返回:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

返回指定索引處的列。唯讀 [Column](../../com.aspose.slides/column)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

建立指定模板 row 的副本，並將其插入表格底部。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的 Column。 |
| withAttachedColumns | boolean | true 表示同時複製所有附屬於模板 row 的列。 |

**返回:**  
com.aspose.slides.IColumn[] - 已新增的列。
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

建立指定模板 column 的副本，並將其插入表格的指定位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新列的索引。 |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 用作模板的 Column。 |
| withAttachedColumns | boolean | true 表示同時複製所有附屬於模板 column 的列。 |

**返回:**  
com.aspose.slides.IColumn[] - 已插入的列。
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

移除表格中指定位置的 column。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| firstColumnIndex | int | 要刪除的列索引。 |
| withAttachedRows | boolean | true 表示同時刪除所有附屬的列。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

返回用於遍歷集合的 enumerator。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

返回整個集合的 java iterator。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的 array。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標 array。 |
| index | int | 目標 array 中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，指示對集合的存取是否同步（執行緒安全）。唯讀 boolean。

**返回:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**返回:**  
java.lang.Object