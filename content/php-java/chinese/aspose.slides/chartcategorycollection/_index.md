---
title: ChartCategoryCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/chartcategorycollection/
---
## ChartCategoryCollection 类

 表示 ChartCategory 的集合

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([ChartDataCell](../chartdatacell)) | 如果集合中已存在该类别，则返回它。否则从 IChartDataCell 创建新的 chart category 并将其添加到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | [ChartDataCell](../chartdatacell) | 用于创建 chart category 的 Cell。 |

 **返回:**
[ChartCategory](../chartcategory)

---

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (Object) | 从值创建新的 ChartCategory 并将其添加到集合中。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | Object | 值。本方法会创建名为 AUTO_DATA 的工作表并将所有值添加到其中。如果使用 ChartDataWorkbook 添加或编辑单元格值，请确保不使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。 |

 **返回:**
[ChartCategory](../chartcategory)

 **异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 超出限制时 |

---

### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中删除所有元素。 |

 **返回:**
void

---

### getGroupingLevelCount {#getGroupingLevelCount}

| 名称 | 描述 |
| --- | --- |
| getGroupingLevelCount () | 返回使用的类别分组级别计数。多级类别时大于 1。只读 int。 |

 **返回:**
int

---

### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回可用于同步访问集合的对象。只读 Object。返回同步根。只读 Object。 |

 **返回:**
Object

---

### getUseCells {#getUseCells}

| 名称 | 描述 |
| --- | --- |
| getUseCells () | 如果为 true，则使用工作表存储类别（此情况支持多层类别）。如果为 false，则不使用工作表存储值（此情况不支持多层类别）。读/写 boolean。 |

 **返回:**
boolean

---

### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。 |

 **返回:**
[ChartCategory](../chartcategory)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 索引在 IList 中不是有效索引。 |

---

### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([ChartCategory](../chartcategory)) | 在整个集合中搜索指定的 ChartCategory 并返回首次出现的零基索引。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartCategory](../chartcategory) | Chart category。 |

 **返回:**
int

---

### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对 List 的访问是否已同步（线程安全）。只读 boolean。 |

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
| remove ([ChartCategory](../chartcategory)) | 删除指定的值。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [ChartCategory](../chartcategory) | 值。 |

 **返回:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 在集合中未找到 value 参数。 |

---

### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 删除给定索引处的元素。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的类别的索引。 |

 **返回:**
void

---

### setUseCells {#setUseCells}

| 名称 | 描述 |
| --- | --- |
| setUseCells (boolean) | 如果为 true，则使用工作表存储类别（此情况支持多层类别）。如果为 false，则不使用工作表存储值（此情况不支持多层类别）。读/写 boolean。 |

 **返回:**
void

---

### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中元素的数量。只读 int。 |

 **返回:**
int

---