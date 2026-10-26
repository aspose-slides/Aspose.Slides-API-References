---
title: SensitivityLabelCollection
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/sensitivitylabelcollection/
---
## SensitivityLabelCollection 类

表示应用于文档的敏感性标签集合。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, UUID, boolean, int) | 在集合末尾添加敏感性标签。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| id | String | 敏感性标签的 id。 |
| siteId | UUID | Azure Active Directory (Azure AD) 站点标识符。 |
| isEnabled | boolean | 标志指示敏感性标签是否已启用。 |
| methodType | int | 敏感性标签的分配方法。 |

**返回值:**
[SensitivityLabel](../sensitivitylabel)

---

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([SensitivityLabel](../sensitivitylabel)) | 向集合中添加 SensitivityLabel。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| label | [SensitivityLabel](../sensitivitylabel) | 要添加到集合末尾的 SensitivityLabel 对象。 |

**返回值:**
int

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 当具有相同 Id 的敏感性标签已添加时抛出。 |

---

### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有元素。 |

**返回值:**
void

---

### copyTo {#copyTo}

| 名称 | 描述 |
| --- | --- |
| copyTo (com.aspose.slides.ISensitivityLabel[], int) | 将集合中的所有元素复制到指定数组。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.slides.ISensitivityLabel[] | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

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
| get_Item (int) | 通过索引返回敏感性标签。 |

**返回值:**
[SensitivityLabel](../sensitivitylabel)

---

### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

**返回值:**



---

### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 删除指定索引处的敏感性标签。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应被删除的敏感性标签的索引。 |

**返回值:**
void

---