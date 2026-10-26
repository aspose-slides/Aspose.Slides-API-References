---
title: SummaryZoomSectionCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/summaryzoomsectioncollection/
---
## SummaryZoomSection 类

表示 Summary Zoom Section 对象的集合。

### addSummaryZoomSection {#addSummaryZoomSection}

| Name | Description |
| --- | --- |
| addSummaryZoomSection ([Section](../section)) | 创建新的 Summary Zoom Section 对象并将其添加到集合中 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | 用于新建 Summary Zoom Section 元素的 Section ISection。如果集合中已存在该 Section 的元素，则返回现有元素。 |

**返回:**
[SummaryZoomSection](../summaryzoomsection)

**异常**

| Error | Condition |
| --- | --- |
|  | ArgumentException | 引用的 section 不属于当前演示文稿或不包含任何幻灯片。 |

---

### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | 从集合中移除所有 SummaryZoomSection 对象。 |

**返回:**
void

---

### getSummarySection {#getSummarySection}

| Name | Description |
| --- | --- |
| getSummarySection ([Section](../section)) | 返回给定 section 的 Summary Zoom Section 元素。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | 用于查找的 Section ISection |

**返回:**
[SummaryZoomSection](../summaryzoomsection)

---

### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

**返回:**
Object

---

### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 ISummaryZoomSection。 |

**返回:**
[SummaryZoomSection](../summaryzoomsection)

---

### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomSection](../summaryzoomsection)) | 返回指定 SummaryZoomSection 对象的索引。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [SummaryZoomSection](../summaryzoomsection) | 要查找的 SummaryZoomSection 对象 ISummaryZoomSection。 |

**返回:**
int

---

### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | 返回指示集合访问是否同步（线程安全）的值。只读 boolean。 |

**返回:**
boolean

---

### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

**返回:**



---

### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回:**



---

### removeSummaryZoomSection {#removeSummaryZoomSection}

| Name | Description |
| --- | --- |
| removeSummaryZoomSection ([Section](../section)) | 从集合中删除 Summary Zoom Section 对象。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | 要移除其 Summary Zoom Section 元素的 Section ISection。 |

**返回:**
void

---

### size {#size}

| Name | Description |
| --- | --- |
| size () | 获取集合实际包含的元素数量。只读 int。 |

**返回:**
int

---