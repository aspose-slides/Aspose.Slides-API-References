---
title: CustomXmlPartCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/customxmlpartcollection/
---
## CustomXmlPartCollection 类

 表示自定义 XML 部分的集合。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String) | 添加新的自定义 XML 部分。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xmlString | String | 要添加的新部分的 xml 字符串。 |

 **返回值:**
[CustomXmlPart](../customxmlpart)

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | xmlString 为空或 xml-data 无效。 |


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (byte[]) | 添加新的自定义 XML 部分。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xmlData | byte[] | 要添加的新部分的 xml 数据。 |

 **返回值:**
[CustomXmlPart](../customxmlpart)

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | xmlData 为空或无效。 |


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (InputStream) | 添加新的自定义 XML 部分。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | InputStream | 包含要添加的新部分 xml 数据的 inputStream。 |

 **返回值:**
[CustomXmlPart](../customxmlpart)

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | inputStream 中的数据为空或无效。 |


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有项。 |

 **返回值:**
void


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回值:**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回指定索引处的元素。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的元素的零基索引。 |

 **返回值:**
[CustomXmlPart](../customxmlpart)

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index 小于 0 或 index 等于或大于 Count |


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。 |

 **返回值:**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

 **返回值:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回值:**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([CustomXmlPart](../customxmlpart)) | 从集合中删除首次出现的特定对象。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [CustomXmlPart](../customxmlpart) | 要删除的自定义 XML 部分。 |

 **返回值:**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentNullException | item 为 null。 |


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 在指定索引处移除自定义 XML 部分。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

 **返回值:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index 小于 0 或 index 等于或大于 Count |


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中自定义 XML 部分的计数。只读 int。 |

 **返回值:**
int


---