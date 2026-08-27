---
title: BehaviorPropertyCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/behaviorpropertycollection/
---
## BehaviorPropertyCollection 类

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([BehaviorProperty](../behaviorproperty)) | 向集合添加新属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [BehaviorProperty](../behaviorproperty) | 要添加的属性。 |

**返回值:**
void


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String) | 向集合添加新属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | String | 要添加的属性值。 |

**返回值:**
void


---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([BehaviorProperty](../behaviorproperty)) |  |

**返回值:**
void


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中删除所有属性。 |

**返回值:**
void


---


### contains {#contains}

| 名称 | 描述 |
| --- | --- |
| contains ([BehaviorProperty](../behaviorproperty)) | 确定 IGenericCollection 是否包含特定值。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [BehaviorProperty](../behaviorproperty) | 要在 IGenericCollection 中定位的属性。 |

**返回值:**
boolean


---


### contains {#contains}

| 名称 | 描述 |
| --- | --- |
| contains (String) | 确定 IGenericCollection 是否包含特定值。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | String | 要在 IGenericCollection 中定位的属性值。 |

**返回值:**
boolean


---


### containsItem {#containsItem}

| 名称 | 描述 |
| --- | --- |
| containsItem ([BehaviorProperty](../behaviorproperty)) |  |

**返回值:**
boolean


---


### copyTo {#copyTo}

| 名称 | 描述 |
| --- | --- |
| copyTo (com.aspose.slides.IBehaviorProperty[], int) | 将 IGenericCollection 的元素复制到数组中，从特定的数组索引开始。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.slides.IBehaviorProperty[] | 从 IGenericCollection 复制的元素的目标是一维数组。该数组必须使用从零开始的索引。 |
| arrayIndex | int | 在数组中开始复制的零基索引。 |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.ArgumentException | 源 IGenericCollection 中的元素数量大于从 arrayIndex 到目标数组结束处的可用空间。 |


---


### copyToTArray {#copyToTArray}

| 名称 | 描述 |
| --- | --- |
| copyToTArray (com.aspose.slides.IBehaviorProperty[], int) |  |

**返回值:**
void


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回指定索引处的属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的属性的索引。 |

**返回值:**
[BehaviorProperty](../behaviorproperty)


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([BehaviorProperty](../behaviorproperty)) | 确定 List 中特定项的索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [BehaviorProperty](../behaviorproperty) | 要在 List 中定位的对象。 |

**返回值:**
int


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf (String) | 确定 List 中通过属性值定位的特定项的索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | String | 属性值 |

**返回值:**
int


---


### indexOfItem {#indexOfItem}

| 名称 | 描述 |
| --- | --- |
| indexOfItem ([BehaviorProperty](../behaviorproperty)) |  |

**返回值:**
int


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, [BehaviorProperty](../behaviorproperty)) | 在指定索引处向集合插入新属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入新属性的位置索引。 |
| item | [BehaviorProperty](../behaviorproperty) | 要添加的属性。 |

**返回值:**
void


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, String) | 在指定索引处向集合插入新属性（使用指定的属性值）。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入新属性的位置索引。 |
| propertyValue | String | 要添加的属性值。 |

**返回值:**
void


---


### insertItem {#insertItem}

| 名称 | 描述 |
| --- | --- |
| insertItem (int, [BehaviorProperty](../behaviorproperty)) |  |

**返回值:**
void


---


### isReadOnly {#isReadOnly}

| 名称 | 描述 |
| --- | --- |
| isReadOnly () | 获取一个值，指示 IGenericCollection 是否为只读。只读布尔。 |

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
| iteratorJava () | 返回整个集合的 Java 迭代器。 |

**返回值:**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([BehaviorProperty](../behaviorproperty)) | 从集合中删除指定属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [BehaviorProperty](../behaviorproperty) | 要删除的属性。 |

**返回值:**
boolean


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove (String) | 从集合中删除指定属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | String | 要删除的属性值。 |

**返回值:**
boolean


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 删除指定索引处的属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应该删除的属性的索引。 |

**返回值:**
void


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([BehaviorProperty](../behaviorproperty)) |  |

**返回值:**
boolean


---


### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, [BehaviorProperty](../behaviorproperty)) | 在指定索引处设置属性。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的属性的索引。 |

**返回值:**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中存储的属性数量。只读整数。 |

**返回值:**
int


---