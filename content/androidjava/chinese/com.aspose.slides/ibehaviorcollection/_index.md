---
title: IBehaviorCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示行为效果的集合。
type: docs
url: /zh/com.aspose.slides/ibehaviorcollection/
---
**所有实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

表示行为效果的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的行为。 |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 返回指定索引处的行为。 |
| [getCount()](#getCount--) | 返回集合中行为的数量。 |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | 向集合添加新行为。 |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | 确定 List 中特定项的索引。 |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 在指定索引处向集合插入新行为。 |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | 从集合中移除指定的行为。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引处从集合中移除行为。 |
| [clear()](#clear--) | 从集合中移除所有行为。 |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

返回指定索引处的行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的行为的索引。 |

**返回值：**
[IBehavior](../../com.aspose.slides/ibehavior) - 动画行为。

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

返回指定索引处的行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要返回的行为的索引。 |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中行为的数量。只读 int。

**返回值：**
int

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

向集合添加新行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要添加的行为。 |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

确定 List 中特定项的索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 List 中定位的对象。 |

**返回值：**
int - 如果在列表中找到项，则返回其索引；否则返回 -1。

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

在指定索引处向集合插入新行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新行为应插入的索引。 |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要插入的行为。 |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

从集合中移除指定的行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要移除的行为。 |

**返回值：**
boolean - 如果成功移除行为则返回 True boolean

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

在指定索引处从集合中移除行为。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的行为的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有行为。

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的对象。 |

**返回值：**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到项则返回 true；否则返回 false。