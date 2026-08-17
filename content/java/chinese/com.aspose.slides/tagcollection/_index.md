---
title: TagCollection
second_title: Aspose.Slides for Java API 参考
description: 表示标签的集合，用户定义的字符串对
type: docs
url: /zh/com.aspose.slides/tagcollection/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)  
```
public final class TagCollection implements ITagCollection
```

表示标签的集合（用户定义的字符串对）

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

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中标签的数量。 |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 向集合中添加一个新标签。 |
| [remove(String name)](#remove-java.lang.String-) | 从集合中删除具有指定名称的标签。 |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | 返回集合中指定键的从零开始的索引。 |
| [contains(String name)](#contains-java.lang.String-) | 确定集合是否包含特定名称。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的标签。 |
| [clear()](#clear--) | 从集合中删除所有标签。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 返回指定索引处标签的值。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 返回指定索引处标签的键。 |
| [getNamesOfTags()](#getNamesOfTags--) | 返回标签的名称。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 返回或设置标签的键值对。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 返回或设置标签的键值对。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组中。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```

返回集合中标签的数量。只读 int。

**返回:**  
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

向集合中添加一个新标签。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标签的名称。 |
| value | java.lang.String | 标签的值。 |

**返回:**  
int - 已添加标签的索引。
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

从集合中删除具有指定名称的标签。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的标签名称。 |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

返回集合中指定键的从零开始的索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要在集合中定位的名称。 |

**返回:**  
int - 键的从零开始的索引；如果在集合中找到键，则返回该索引，否则返回 -1。
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

确定集合是否包含特定名称。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要定位的键。 |

**返回:**  
boolean - 如果集合包含具有指定键的标签则为 true；否则为 false。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

删除指定索引处的标签。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的标签的从零开始的索引。 |
### clear() {#clear--}
```
public final void clear()
```

从集合中删除所有标签。
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

返回指定索引处标签的值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的标签的索引。 |

**返回:**  
java.lang.String - 标签的值。
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

返回指定索引处标签的键。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的标签的索引。 |

**返回:**  
java.lang.String - 标签的键。
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

返回标签的名称。

**返回:**  
java.lang.String[] - 标签的名称。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

返回或设置标签的键值对。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标签的键。 |

**返回:**  
java.lang.String - 标签的值。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

返回或设置标签的键值对。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 标签的键。 |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要填充的数组。 |
| index | int | 目标数组中的起始位置。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

返回遍历集合的枚举器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.