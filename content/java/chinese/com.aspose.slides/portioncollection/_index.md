---
title: PortionCollection
second_title: Aspose.Slides 的 Java API 参考
description: 表示一个 Portion 集合。
type: docs
url: /zh/com.aspose.slides/portioncollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

表示一个段落集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取集合中实际包含的元素数量。 |
| [isReadOnly()](#isReadOnly--) | 获取指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读的值。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | 获取指定索引处的元素。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | 将一个 Portion 添加到集合的末尾。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | 确定 List 中特定项的索引。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 在指定索引处向集合插入一个 Portion。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。 |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | 从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 为整个集合返回一个 java 迭代器。 |
### getCount() {#getCount--}
```
public final int getCount()
```

获取集合中实际包含的元素数量。只读 int。

**返回值:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读的值。只读 boolean。

**返回值:**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 为只读则为 true；否则为 false。
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

将一个 Portion 添加到集合的末尾。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 要添加到集合末尾的 Portion。 |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

确定 List 中特定项的索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在 List 中定位的对象。 |

**返回值:**
int - 如果在列表中找到 item，则返回其索引；否则返回 -1。
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

在指定索引处向集合插入一个 Portion。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Portion 的基于零的索引。 |
| value | [IPortion](../../com.aspose.slides/iportion) | 要插入的 Portion。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有元素。

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回值:**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 则为 true；否则为 false。
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组中，从特定的数组索引开始。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | 作为目标的单维数组，接收从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 复制的元素。数组必须使用基于零的索引。 |
| arrayIndex | int | 复制开始的数组基于零的索引。 |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的对象。 |

**返回值:**
boolean - 如果成功从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item 则为 true；否则为 false。如果在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到 item，此方法也返回 false。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的基于零的索引。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

返回一个遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - 可以用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

为整个集合返回一个 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - 整个集合的 java.util.Iterator。