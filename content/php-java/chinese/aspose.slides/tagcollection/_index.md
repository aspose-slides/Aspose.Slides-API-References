---
title: TagCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/tagcollection/
---
## TagCollection 类

 表示标签的集合（用户定义的字符串对）

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, String) | 向集合添加一个新标签。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 标签的名称。 |
| value | String | 标签的值。 |

**返回值：**
int


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有标签。 |

**返回值：**
void


---


### contains {#contains}

| 名称 | 描述 |
| --- | --- |
| contains (String) | 确定集合是否包含特定的名称。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要定位的键。 |

**返回值：**
boolean


---


### getNameByIndex {#getNameByIndex}

| 名称 | 描述 |
| --- | --- |
| getNameByIndex (int) | 返回指定索引处标签的键。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的标签的索引。 |

**返回值：**
String


---


### getNamesOfTags {#getNamesOfTags}

| 名称 | 描述 |
| --- | --- |
| getNamesOfTags () | 返回标签的名称。 |

**返回值：**
String


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

**返回值：**
Object


---


### getValueByIndex {#getValueByIndex}

| 名称 | 描述 |
| --- | --- |
| getValueByIndex (int) | 返回指定索引处标签的值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的标签的索引。 |

**返回值：**
String


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (String) | 返回或设置标签的键和值对。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 标签的键。 |

**返回值：**
String


---


### indexOfName {#indexOfName}

| 名称 | 描述 |
| --- | --- |
| indexOfName (String) | 返回集合中指定键的零基索引。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 集合中要定位的名称。 |

**返回值：**
int


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

**返回值：**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个遍历集合的枚举器。 |

**返回值：**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回值：**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove (String) | 从集合中移除具有指定名称的标签。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要移除的标签的名称。 |

**返回值：**
void


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除指定索引处的标签。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的标签的零基索引。 |

**返回值：**
void


---


### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (String, String) | 返回或设置标签的键和值对。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 标签的键。 |

**返回值：**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中标签的数量。只读 int。 |

**返回值：**
int


---