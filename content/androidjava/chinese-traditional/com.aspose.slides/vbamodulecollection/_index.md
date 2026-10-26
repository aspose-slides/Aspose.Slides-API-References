---
title: VbaModuleCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 VBA 專案模組的集合。
type: docs
url: /zh-hant/com.aspose.slides/vbamodulecollection/
---
**繼承：**
java.lang.Object

**已實作的所有介面：**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

表示 VBA 專案模組的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 獲取集合實際包含的元素數量。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | 從集合中移除首次出現的特定物件。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | 向 VBA 專案新增一個空模組。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [iterator()](#iterator--) | 返回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將所有元素從集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

獲取集合實際包含的元素數量。唯讀 int。

**返回：**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

從集合中移除首次出現的特定物件。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | 要從集合中移除的模組。 |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

向 VBA 專案新增一個空模組。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 模組名稱 |

**返回：**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 已添加的模組。
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

返回一個可遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將所有元素從集合複製到指定的陣列。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**返回：**
java.lang.Object