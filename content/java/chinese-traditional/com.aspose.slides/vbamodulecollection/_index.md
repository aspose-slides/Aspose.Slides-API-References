---
title: VbaModuleCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示 VBA 專案模組的集合。
type: docs
url: /zh-hant/com.aspose.slides/vbamodulecollection/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

表示 VBA 專案模組的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | 從集合中移除第一次出現的特定物件。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | 向 VBA 專案新增一個空的模組。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數量。只讀 int。

**傳回：**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

從集合中移除第一次出現的特定物件。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | 要從集合中移除的模組。 |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

向 VBA 專案新增一個空的模組。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 模組的名稱 |

**傳回：**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 已新增的模組。
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

取得指定索引處的元素。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回：**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

傳回遍歷集合的列舉器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否同步（執行緒安全）。只讀 boolean。

**傳回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。只讀 Object。

**傳回：**
java.lang.Object