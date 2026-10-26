---
title: IPointCollection
second_title: 通过 Java API 的 Aspose.Slides Android 参考
description: 表示一组部分的集合。
type: docs
url: /zh/com.aspose.slides/ipointcollection/
---
**已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

表示一组部分的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中点的数量。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的点。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中点的数量。只读 int。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```

返回指定索引处的点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[IPoint](../../com.aspose.slides/ipoint) - 该 [IPoint](../../com.aspose.slides/ipoint) 对象。