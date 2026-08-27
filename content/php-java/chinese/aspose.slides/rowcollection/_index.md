---
title: RowCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/rowcollection/
---
## RowCollection 类

 表示表格行集合。

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Row](../row), boolean) | 创建指定模板行的副本并将其插入表格的底部。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| templ | [Row](../row) | 用作模板的 Row。 |
| withAttachedRows | boolean | True 表示同时复制附加到模板行的所有行。 |

 **返回值:**
[Row](../row)

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
| get_Item (int) | 返回指定索引处的 Row。只读 Row。 |

 **返回值:**
[Row](../row)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Row](../row), boolean) | 创建指定模板行的副本并将其插入表格的指定位置。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新行的索引。 |
| templ | [Row](../row) | 用作模板的 Row。 |
| withAttachedRows | boolean | True 表示同时复制附加到模板行的所有行。 |

 **返回值:**
[Row](../row)

---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

 **返回值:**
boolean

---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

 **返回值:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回值:**



---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int, boolean) | 删除表格中指定位置的行。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| firstRowIndex | int | 要删除的行的索引。 |
| withAttachedRows | boolean | True 表示同时删除所有附加的行。 |

 **返回值:**
void

---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 获取集合实际包含的行数。只读 int。 |

 **返回值:**
int

---  