---
title: CaptionsCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/captionscollection/
---
## CaptionsCollection 类

表示闭合字幕的集合。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, String) | 将 WebVTT 闭合字幕添加到集合的末尾。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| label | String | 闭合字幕的标签。 |
| filePath | String | WebVTT 文件的路径。 |

**返回值:**
[Captions](../captions)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果 filePath 为空则抛出。 |

---

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, InputStream) | 从流中将 WebVTT 闭合字幕添加到集合的末尾。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| label | String | 闭合字幕的标签。 |
| stream | InputStream | 包含 WebVTT 格式数据的输入流。 |

**返回值:**
[Captions](../captions)

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果输入数据不是 WebVTT 格式则抛出。 |

---

### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有闭合字幕。 |

**返回值:**
void

---

### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 返回集合中元素的数量。只读 int。 |

**返回值:**
int

---

### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回指定索引处的闭合字幕。只读 ICaptions。 |

**返回值:**
[Captions](../captions)

---

### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个遍历集合的枚举器。 |

**返回值:**



---

### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Captions](../captions)) | 从集合中移除指定的闭合字幕。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| captions | [Captions](../captions) | 要移除的闭合字幕。 |

**返回值:**
void

---

### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除指定索引处的闭合字幕。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的闭合字幕的索引。 |

**返回值:**
void

---