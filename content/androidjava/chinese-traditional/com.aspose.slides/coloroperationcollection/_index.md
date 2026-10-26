---
title: ColorOperationCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示一個顏色變換操作的集合。
type: docs
url: /zh-hant/com.aspose.slides/coloroperationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

表示一個顏色變換操作的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 返回集合中操作的數目。 |
| [get_Item(int index)](#get-Item-int-) | 返回或設定指定索引處的操作。 |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 返回或設定指定索引處的操作。 |
| [add(int operation, float parameter)](#add-int-float-) | 在集合末端新增一個操作。 |
| [add(int operation)](#add-int-) | 在集合末端新增一個操作。 |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 在集合中插入新的操作。 |
| [insert(int position, int operation)](#insert-int-int-) | 在集合中插入新的操作。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除顏色操作。 |
| [clear()](#clear--) | 移除所有顏色操作。 |
| [iterator()](#iterator--) | 返回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指示對集合的存取是否同步 (執行緒安全)。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [deepClone()](#deepClone--) | 建立 ColorOperationCollection 集合的副本。 |
| [cloneT()](#cloneT--) | 克隆目前物件 |
### size() {#size--}
```
public final int size()
```

返回集合中操作的數目。唯讀 int。

**返回值:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

返回或設定指定索引處的操作。讀寫 [ColorOperation](../../com.aspose.slides/coloroperation)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值:**  
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

返回或設定指定索引處的操作。讀寫 [ColorOperation](../../com.aspose.slides/coloroperation)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

在集合末端新增一個操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operation | int | 操作類型。 |
| parameter | float | 操作的參數。 |

**返回值:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已新增的操作。
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

在集合末端新增一個操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operation | int | 操作類型。 |

**返回值:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已新增的操作。
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

在集合中插入新的操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作類型。 |
| parameter | float | 操作的參數。 |

**返回值:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

在集合中插入新的操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作類型。 |

**返回值:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中移除顏色操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的顏色操作索引。 |
### clear() {#clear--}
```
public final void clear()
```

移除所有顏色操作。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

返回用於遍歷集合的列舉器。

**返回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 用於整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，指示對集合的存取是否同步 (執行緒安全)。唯讀 boolean。

**返回值:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**返回值:**  
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

建立 ColorOperationCollection 集合的副本。

**返回值:**  
java.lang.Object - 新的 [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) 集合。
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

克隆目前物件

**返回值:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - 複製品