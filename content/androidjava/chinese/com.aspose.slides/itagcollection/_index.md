---
title: ITagCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示用户定义的字符串对的标签集合
type: docs
url: /zh/com.aspose.slides/itagcollection/
---
**已实现的所有接口：**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

表示标签的集合（用户定义的字符串对）

## 方法

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 向集合中添加新标签。 |
| [remove(String name)](#remove-java.lang.String-) | 从集合中移除具有指定名称的标签。 |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | 返回集合中指定键的从零开始的索引。 |
| [contains(String name)](#contains-java.lang.String-) | 确定集合是否包含特定名称。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引处的标签。 |
| [clear()](#clear--) | 移除集合中的所有标签。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 返回指定索引处标签的值。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 返回指定索引处标签的键。 |
| [getNamesOfTags()](#getNamesOfTags--) | 返回标签的名称。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 返回或设置标签的键值对。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 返回或设置标签的键值对。 |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

向集合中添加新标签。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 标签的名称。 |
| value | java.lang.String | 标签的值。 |

**返回：**
int - 添加的标签的索引。

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

从集合中移除具有指定名称的标签。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 要移除的标签的名称。 |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

返回集合中指定键的从零开始的索引。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 要在集合中定位的名称。 |

**返回：**
int - 键的从零开始的索引，如果在集合中找到键；否则为 -1。

### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

确定集合是否包含特定名称。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 要定位的键。 |

**返回：**
boolean - 如果集合包含具有指定键的标签，则为 true；否则为 false。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引处的标签。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的标签的从零开始的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有标签。

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

返回指定索引处标签的值。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要返回的标签的索引。 |

**返回：**
java.lang.String - 标签的值。

### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

返回指定索引处标签的键。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要返回的标签的索引。 |

**返回：**
java.lang.String - 标签的键。

### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

返回标签的名称。

**返回：**
java.lang.String[] - 标签的名称数组。

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

返回或设置标签的键值对。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 标签的键。 |

**返回：**
java.lang.String - 标签的值。

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

返回或设置标签的键值对。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 标签的键。 |
| value | java.lang.String |  |