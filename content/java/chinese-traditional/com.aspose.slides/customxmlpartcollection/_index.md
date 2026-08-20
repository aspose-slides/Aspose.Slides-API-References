---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Java API 參考
description: 表示自訂 XML 部分的集合。
type: docs
url: /zh-hant/com.aspose.slides/customxmlpartcollection/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

表示自訂 XML 部分的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的元素。 |
| [size()](#size--) | 傳回集合中自訂 XML 部分的計數。 |
| [add(String xmlString)](#add-java.lang.String-) | 新增自訂 XML 部分。 |
| [add(byte[] xmlData)](#add-byte---) | 新增自訂 XML 部分。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 新增自訂 XML 部分。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的自訂 XML 部分。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | 從集合中移除第一個特定物件的出現。 |
| [clear()](#clear--) | 移除集合中所有項目。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 複製至指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉子。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

傳回指定索引處的元素。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要取得之元素的零基索引。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 指定索引處的元素。
### size() {#size--}
```
public final int size()
```

傳回集合中自訂 XML 部分的計數。唯讀 int。

**傳回值：**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

新增自訂 XML 部分。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| xmlString | java.lang.String | 要新增之部件的 XML 字串。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

新增自訂 XML 部分。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| xmlData | byte[] | 要新增之部件的 XML 資料。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

新增自訂 XML 部分。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要新增之部件的 XML 資料的 inputStream。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引處的自訂 XML 部分。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

從集合中移除第一個特定物件的出現。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 要移除的自訂 XML 部分。 |

**傳回值：**
boolean - true if item is successfully removed; otherwise, false.
### clear() {#clear--}
```
public final void clear()
```

移除集合中所有項目。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

複製至指定的陣列。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要複製至的陣列。 |
| index | int | 開始複製的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否同步（執行緒安全）。唯讀 boolean。

**傳回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值：**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

傳回可遍歷集合的列舉子。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 可用於遍歷整個集合的 java.util.Iterator。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject