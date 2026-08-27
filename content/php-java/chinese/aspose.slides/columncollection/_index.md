---
title: ColumnCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/columncollection/
---
## ColumnCollection 类

 表示表格中列的集合。

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Column](../column), boolean) | 创建指定模板行的副本并将其插入表格的底部。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| templ | [Column](../column) | 用作模板的列。 |
| withAttachedColumns | boolean | True 表示同时复制模板行附带的所有列。 |

**返回值：**
[Column](../column)

---

### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

**返回值：**
Object

---

### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回指定索引处的列。只读 Column。 |

**返回值：**
[Column](../column)

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Column](../column), boolean) | 创建指定模板列的副本并将其插入表格中指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新列的索引。 |
| templ | [Column](../column) | 用作模板的列。 |
| withAttachedColumns | boolean | True 表示同时复制模板列附带的所有列。 |

**返回值：**
[Column](../column)

---

### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。 |

**返回值：**
boolean

---

### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

**返回值：**



---

### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回值：**



---

### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int, boolean) | 从表格中指定位置删除列。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| firstColumnIndex | int | 要删除的列的索引。 |
| withAttachedRows | boolean | True 表示同时删除所有附带的列。 |

**返回值：**
void

---

### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中列的数量。只读 int。 |

**返回值：**
int

---