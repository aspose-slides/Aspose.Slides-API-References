---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示自定义 XML 部分的集合。
type: docs
url: /zh/com.aspose.slides/customxmlpartcollection/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

表示自定义 XML 部分的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的元素。 |
| [size()](#size--) | 返回集合中自定义 XML 部分的计数。 |
| [add(String xmlString)](#add-java.lang.String-) | 添加新的自定义 XML 部分。 |
| [add(byte[] xmlData)](#add-byte---) | 添加新的自定义 XML 部分。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 添加新的自定义 XML 部分。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引处的自定义 XML 部分。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | 从集合中移除首次出现的特定对象。 |
| [clear()](#clear--) | 移除集合中的所有项。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根对象。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 Java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

返回指定索引处的元素。

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

返回集合中自定义 XML 部分的计数。只读 int。

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
| inputStream | java.io.InputStream | 包含要添加的新部分 XML 数据的输入流。 |

**返回：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 创建的自定义 XML 部分。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引处的自定义 XML 部分。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

从集合中移除首次出现的特定对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 要移除的自定义 XML 部分。 |

**返回：**
boolean - 若成功移除则为 true；否则为 false。
### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有项。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

复制到指定数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要复制到的数组。 |
| index | int | 开始复制的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回指示集合访问是否同步（线程安全）的值。只读 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根对象。只读 Object。

**返回：**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

返回整个集合的 Java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - 用于整个集合的 java.util.Iterator。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject