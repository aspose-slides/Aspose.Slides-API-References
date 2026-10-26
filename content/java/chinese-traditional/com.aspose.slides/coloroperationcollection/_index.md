---
title: ColorOperationCollection
second_title: Aspose.Slides for Java API 參考
description: 表示一個顏色變換運算的集合。
type: docs
url: /zh-hant/com.aspose.slides/coloroperationcollection/
---
**繼承:**  
java.lang.Object

**所有實作的介面:**  
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)  
```
public final class ColorOperationCollection implements IColorOperationCollection
```

表示一個顏色變換運算的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 傳回集合中運算的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回或設定指定索引處的運算。 |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 傳回或設定指定索引處的運算。 |
| [add(int operation, float parameter)](#add-int-float-) | 在集合的末端新增一個運算。 |
| [add(int operation)](#add-int-) | 在集合的末端新增一個運算。 |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 將新的運算插入集合中。 |
| [insert(int position, int operation)](#insert-int-int-) | 將新的運算插入集合中。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除顏色運算。 |
| [clear()](#clear--) | 移除所有顏色運算。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，表示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [deepClone()](#deepClone--) | 建立 ColorOperationCollection 集合的副本。 |
| [cloneT()](#cloneT--) | 克隆當前物件 |

### size() {#size--}
```
public final int size()
```

傳回集合中運算的數量。 唯讀 int。

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

傳回或設定指定索引處的運算。 讀寫 [ColorOperation](../../com.aspose.slides/coloroperation)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

傳回或設定指定索引處的運算。 讀寫 [ColorOperation](../../com.aspose.slides/coloroperation)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

在集合的末端新增一個運算。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operation | int | 運算類型。 |
| parameter | float | 運算的參數。 |

**傳回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已新增的運算。

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

在集合的末端新增一個運算。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| operation | int | 運算類型。 |

**傳回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已新增的運算。

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

將新的運算插入集合中。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | int | 要插入運算的索引位置。 |
| operation | int | 運算類型。 |
| parameter | float | 運算的參數。 |

**傳回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的運算。

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

將新的運算插入集合中。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | int | 要插入運算的索引位置。 |
| operation | int | 運算類型。 |

**傳回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的運算。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中移除顏色運算。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的顏色運算的索引。 |

### clear() {#clear--}
```
public final void clear()
```

移除所有顏色運算。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

傳回可遍歷集合的列舉器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 整個集合的 java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中所有元素複製到指定的陣列。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，表示對集合的存取是否已同步（執行緒安全）。 唯讀 boolean。

**傳回:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。 唯讀 Object。

**傳回:**  
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

建立 ColorOperationCollection 集合的副本。

**傳回:**  
java.lang.Object - 新的 [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) 集合。

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

克隆當前物件

**傳回:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - 克隆