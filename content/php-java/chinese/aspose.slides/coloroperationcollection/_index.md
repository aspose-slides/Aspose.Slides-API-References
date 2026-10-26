---
title: ColorOperationCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/coloroperationcollection/
---
## ColorOperationCollection 类

 表示一组颜色变换操作。
 
### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (int, float) | 向集合末尾添加一个新操作。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |
| parameter | float | 操作的参数。 |

 **返回:**
[ColorOperation](../coloroperation)


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (int) | 向集合末尾添加一个新操作。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |

 **返回:**
[ColorOperation](../coloroperation)


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 删除所有颜色操作。 |

 **返回:**
void


---


### cloneT {#cloneT}

| 名称 | 描述 |
| --- | --- |
| cloneT () | 克隆当前对象 |

 **返回:**
[ColorOperationCollection](../coloroperationcollection)


---


### deepClone {#deepClone}

| 名称 | 描述 |
| --- | --- |
| deepClone () | 创建 ColorOperationCollection 集合的副本。 |

 **返回:**
Object


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回:**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回或设置指定索引处的操作。读/写 ColorOperation。 |

 **返回:**
[ColorOperation](../coloroperation)


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, int, float) | 将新操作插入集合。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作类型。 |
| parameter | float | 操作的参数。 |

 **返回:**
[ColorOperation](../coloroperation)


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, int) | 将新操作插入集合。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作类型。 |

 **返回:**
[ColorOperation](../coloroperation)


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

 **返回:**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

 **返回:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回:**



---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 从集合中删除颜色操作。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的颜色操作的索引。 |

 **返回:**
void


---


### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, [ColorOperation](../coloroperation)) | 返回或设置指定索引处的操作。读/写 ColorOperation。 |

 **返回:**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中操作的数量。只读 int。 |

 **返回:**
int


---