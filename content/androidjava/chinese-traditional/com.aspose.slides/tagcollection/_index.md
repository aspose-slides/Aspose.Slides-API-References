---
title: TagCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示使用者自訂的字串對標籤集合
type: docs
url: /zh-hant/com.aspose.slides/tagcollection/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

代表標籤的集合（使用者定義的字串對）

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回集合中標籤的數量。 |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 將新標籤加入集合。 |
| [remove(String name)](#remove-java.lang.String-) | 從集合中移除具有指定名稱的標籤。 |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | 傳回集合中指定鍵的零基索引。 |
| [contains(String name)](#contains-java.lang.String-) | 判斷集合是否包含特定名稱。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的標籤。 |
| [clear()](#clear--) | 從集合中移除所有標籤。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 傳回指定索引處標籤的值。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 傳回指定索引處標籤的鍵。 |
| [getNamesOfTags()](#getNamesOfTags--) | 傳回標籤的名稱。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 取得或設定標籤的鍵值對。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 取得或設定標籤的鍵值對。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```

傳回集合中標籤的數量。唯讀 int。

**傳回值:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

將新標籤加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 標籤的名稱。 |
| value | java.lang.String | 標籤的值。 |

**傳回值:**
int - 新增標籤的索引。
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

從集合中移除具有指定名稱的標籤。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要移除的標籤名稱。 |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

傳回集合中指定鍵的零基索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要在集合中定位的名稱。 |

**傳回值:**
int - 若在集合中找到鍵，則傳回其零基索引；否則傳回 -1。
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

判斷集合是否包含特定名稱。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要定位的鍵。 |

**傳回值:**
boolean - 若集合包含具有指定鍵的標籤，則傳回 true；否則傳回 false。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引處的標籤。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的標籤的零基索引。 |
### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有標籤。
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

傳回指定索引處標籤的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要傳回的標籤索引。 |

**傳回值:**
java.lang.String - 標籤的值。
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

傳回指定索引處標籤的鍵。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要傳回的標籤索引。 |

**傳回值:**
java.lang.String - 標籤的鍵。
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

傳回標籤的名稱。

**傳回值:**
java.lang.String[] - 標籤的名稱。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

取得或設定標籤的鍵值對。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 標籤的鍵。 |

**傳回值:**
java.lang.String - 標籤的值。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

取得或設定標籤的鍵值對。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 標籤的鍵。 |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要填充的陣列。 |
| index | int | 目標陣列的起始位置。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回值:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

傳回用於遍歷集合的列舉器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.