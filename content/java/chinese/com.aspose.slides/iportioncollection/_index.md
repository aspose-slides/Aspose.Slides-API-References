---
title: IPortionCollection
second_title: Aspose.Slides Java API 参考
description: 表示一个 Portion 的集合。
type: docs
url: /zh/com.aspose.slides/iportioncollection/
---
**已实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

表示一个 Portion 的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getCount()](#getCount--) | 获取集合实际包含的元素数量。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | 在集合末尾添加一个 Portion。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | 确定集合中特定 Portion 的索引。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 在指定索引处向集合插入一个 Portion。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | 从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合实际包含的元素数量。只读 int。

**返回:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

在集合末尾添加一个 Portion。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 要添加到集合末尾的 Portion。 |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

确定集合中特定 Portion 的索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在集合中定位的 Portion。 |

**返回:**
int - 如果在集合中找到项，则返回其索引；否则返回 -1。
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

在指定索引处向集合插入一个 Portion。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 Portion 的基于零的索引。 |
| value | [IPortion](../../com.aspose.slides/iportion) | 要插入的 Portion。 |

### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有元素。

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回:**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到项，则为 true；否则为 false。
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定对象的第一次出现。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的对象。 |

**返回:**
boolean - 如果成功从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除项，则为 true；否则为 false。如果在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到项，此方法也返回 false。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的基于零的索引。 |