---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示自訂 XML 部分的集合。
type: docs
url: /zh-hant/com.aspose.slides/customxmlpartcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

表示自訂 XML 部分的集合。

## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的元素。 |
| [size()](#size--) | 返回集合中自訂 XML 部分的計數。 |
| [add(String xmlString)](#add-java.lang.String-) | 新增自訂 XML 部分。 |
| [add(byte[] xmlData)](#add-byte---) | 新增自訂 XML 部分。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 新增自訂 XML 部分。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的自訂 XML 部分。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | 從集合中移除第一個特定物件的出現。 |
| [clear()](#clear--) | 移除集合中的所有項目。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 複製至指定陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

返回指定索引處的元素。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要取得的元素之零基索引。 |

**返回：**  
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 指定索引處的元素。

### size() {#size--}
```
public final int size()
```

返回集合中自訂 XML 部分的計數。只讀 int。

**返回：**  
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

新增自訂 XML 部分。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlString | java.lang.String | 要新增之新部分的 XML 字串。 |

**返回：**  
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

新增自訂 XML 部分。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlData | byte[] | 要新增之新部分的 XML 資料。 |

**返回：**  
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

新增自訂 XML 部分。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 包含要新增之新部分 XML 資料的 inputStream。 |

**返回：**  
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引處的自訂 XML 部分。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

從集合中移除第一個特定物件的出現。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 要移除的自訂 XML 部分。 |

**返回：**  
boolean - 若成功移除項目則為 true；否則為 false。

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有項目。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

複製至指定陣列。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要複製至的陣列。 |
| index | int | 開始複製的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，指示對集合的存取是否已同步（執行緒安全）。只讀 boolean。

**返回：**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只讀 Object。

**返回：**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

返回可遍歷集合的列舉器。

**返回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 整個集合的 java.util.Iterator。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。只讀 IDOMObject。

**返回：**  
com.aspose.slides.IDOMObject