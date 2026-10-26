---
title: PortionCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/portioncollection/
---
## PortionCollection 类

 表示一个 Portion 集合。
 
### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([MathPortion](../mathportion)) | 将 Portion 添加到集合的末尾。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [MathPortion](../mathportion) | 要添加到集合末尾的 Portion。 |

 **返回值：**
void


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([Portion](../portion)) | 将 Portion 添加到集合的末尾。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [Portion](../portion) | 要添加到集合末尾的 Portion。 |

 **返回值：**
void


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有元素。 |

 **返回值：**
void


---


### contains {#contains}

| 名称 | 描述 |
| --- | --- |
| contains ([MathPortion](../mathportion)) | 确定 IGenericCollection 是否包含特定值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [MathPortion](../mathportion) | 要在 IGenericCollection 中定位的对象。 |

 **返回值：**
boolean


---


### contains {#contains}

| 名称 | 描述 |
| --- | --- |
| contains ([Portion](../portion)) | 确定 IGenericCollection 是否包含特定值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Portion](../portion) | 要在 IGenericCollection 中定位的对象。 |

 **返回值：**
boolean


---


### copyTo {#copyTo}

| 名称 | 描述 |
| --- | --- |
| copyTo (com.aspose.slides.IPortion[], int) | 将 IGenericCollection 的元素复制到数组中，从特定的数组索引开始。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.slides.IPortion[] | 一维数组，作为从 IGenericCollection 复制的元素的目标。该数组必须使用零基索引。 |
| arrayIndex | int | 复制开始的数组零基索引。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | 源 IGenericCollection 中的元素数量大于从 arrayIndex 到目标数组末尾可用的空间。 |


---


### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 获取集合实际包含的元素数量。只读 int。 |

 **返回值：**
int


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。 |

 **返回值：**
[MathPortion](../mathportion), [Portion](../portion)


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([MathPortion](../mathportion)) | 确定 List 中特定项的索引。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [MathPortion](../mathportion) | 要在 List 中定位的对象。 |

 **返回值：**
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([Portion](../portion)) | 确定 List 中特定项的索引。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Portion](../portion) | 要在 List 中定位的对象。 |

 **返回值：**
int


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, [MathPortion](../mathportion)) | 在指定索引处将 Portion 插入到集合中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入 Portion 的零基索引。 |
| value | [MathPortion](../mathportion) | 要插入的 Portion。 |

 **返回值：**
void


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, [Portion](../portion)) | 在指定索引处将 Portion 插入到集合中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入 Portion 的零基索引。 |
| value | [Portion](../portion) | 要插入的 Portion。 |

 **返回值：**
void


---


### isReadOnly {#isReadOnly}

| 名称 | 描述 |
| --- | --- |
| isReadOnly () | 获取一个值，指示 IGenericCollection 是否为只读。只读 boolean。 |

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
| remove ([MathPortion](../mathportion)) | 从 IGenericCollection 中移除特定对象的第一次出现。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [MathPortion](../mathportion) | 要从 IGenericCollection 中移除的对象。 |

 **返回值：**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.NotSupportedException | IGenericCollection 为只读。 |


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Portion](../portion)) | 从 IGenericCollection 中移除特定对象的第一次出现。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Portion](../portion) | 要从 IGenericCollection 中移除的对象。 |

 **返回值：**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.NotSupportedException | IGenericCollection 为只读。 |


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除集合中指定索引处的元素。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

 **返回值：**
void


---


### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, [MathPortion](../mathportion)) | 获取指定索引处的元素。 |

 **返回值：**
void


---


### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, [Portion](../portion)) | 获取指定索引处的元素。 |

 **返回值：**
void


---