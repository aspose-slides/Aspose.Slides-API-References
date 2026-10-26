---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Java API 参考
description: 表示自定义 XML 部分的集合。
type: docs
url: /zh/com.aspose.slides/customxmlpartcollection/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

表示自定义 XML 部分的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 在指定索引处返回元素。 |
| [size()](#size--) | 返回集合中自定义 XML 部分的数量。 |
| [add(String xmlString)](#add-java.lang.String-) | 添加新的自定义 XML 部分。 |
| [add(byte[] xmlData)](#add-byte---) | 添加新的自定义 XML 部分。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 添加新的自定义 XML 部分。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引处移除自定义 XML 部分。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | 从集合中移除特定对象的首次出现。 |
| [clear()](#clear--) | 从集合中移除所有项目。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 复制到指定的数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 Java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

在指定索引处返回元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的元素的零基索引。 |

**返回：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 指定索引处的元素。

### size() {#size--}
```
public final int size()
```

返回集合中自定义 XML 部分的数量。只读 int。

**返回：**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

添加新的自定义 XML 部分。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlString | java.lang.String | 要添加的新部分的 XML 字符串。 |

**返回：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 创建的自定义 XML 部分。

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

添加新的自定义 XML 部分。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlData | byte[] | 要添加的新部分的 XML 数据。 |

**返回：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 创建的自定义 XML 部分。

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

添加新的自定义 XML 部分。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 包含要添加的新部分 XML 数据的 inputStream。 |

**返回：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 创建的自定义 XML 部分。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定索引处移除自定义 XML 部分。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

从集合中移除特定对象的首次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 要移除的自定义 XML 部分。 |

**返回：**
boolean - 如果成功删除项目则为 true；否则为 false。

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有项目。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

复制到指定的数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要复制到的数组。 |
| index | int | 开始复制的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回：**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

返回整个集合的 Java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 用于遍历整个集合的 java.util.Iterator。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject