---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Java API 参考
description: 表示可调节绘图参考线的集合。
type: docs
url: /zh/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

表示可调节绘图参考线的集合。
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的绘图参考线。 |
| [add(byte orientation, float position)](#add-byte-float-) | 在集合末尾添加绘图参考线。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的绘图参考线。 |
| [clear()](#clear--) | 删除集合中的所有元素。 |
| [getCount()](#getCount--) | 获取集合中所有元素的数量。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

返回指定索引的绘图参考线。只读 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

在集合末尾添加绘图参考线。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientation | byte | 绘图参考线的方向。 |
| position | float | 绘图参考线的位置（单位：点）。 |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的绘图参考线。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要删除的绘图参考线的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

删除集合中的所有元素。

### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合中所有元素的数量。只读 int。

**Returns:**
int