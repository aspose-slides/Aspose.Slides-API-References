---
title: ControlCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/controlcollection/
---
## ControlCollection 类

 ActiveX 控件的集合。
 
### addControl {#addControl}

| 名称 | 描述 |
| --- | --- |
| addControl (int, float, float, float, float) | 创建并将新控件添加到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| controlType | int | 要添加的控件类型。 |
| x | float | 形状框左侧的 X 坐标。 |
| y | float | 形状框顶部的 Y 坐标。 |
| width | float | 形状框的宽度。 |
| height | float | 形状框的高度。 |

 **返回:**
[Control](../control)


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有控件。 |

 **返回:**
void


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
| get_Item (int) | 返回指定位置的控件。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 控件的索引。 |

 **返回:**
[Control](../control)


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


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Control](../control)) | 从集合中移除 ActiveX 控件。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Control](../control) | 要移除的控件。 |

 **返回:**
void


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 从集合中移除存储在指定位置的 ActiveX 控件。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的控件的索引。 |

 **返回:**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中对象的数量。只读 int。 |

 **返回:**
int


---