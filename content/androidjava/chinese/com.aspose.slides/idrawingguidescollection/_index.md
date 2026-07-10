---
title: IDrawingGuidesCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示可调节绘图指南的集合。
type: docs
url: /zh/com.aspose.slides/idrawingguidescollection/
---
**已实现的所有接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

表示可调节绘图指南的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引返回绘图指南。 |
| [add(byte orientation, float position)](#add-byte-float-) | 在集合末尾添加绘图指南。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的绘图指南。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [getCount()](#getCount--) | 获取集合中所有元素的数量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

按索引返回绘图指南。只读 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

在集合末尾添加绘图指南。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orientation | byte | 绘图指南的方向。 |
| position | float | 绘图指南在点中的位置。 |

**返回值:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的绘图指南。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的绘图指南的索引。 |
### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有元素。

### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合中所有元素的数量。只读 int。

**返回值:**
int