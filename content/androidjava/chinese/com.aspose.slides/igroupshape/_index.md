---
title: IGroupShape
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示幻灯片上的一组形状。
type: docs
url: /zh/com.aspose.slides/igroupshape/
---
**所有实现的接口：**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGroupShape extends IShape
```

表示幻灯片上的一组形状。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGroupShapeLock()](#getGroupShapeLock--) | 返回形状的锁定。 |
| [getShapes()](#getShapes--) | 返回组内形状的集合。 |
### getGroupShapeLock() {#getGroupShapeLock--}
```
public abstract IGroupShapeLock getGroupShapeLock()
```

返回形状的锁定。只读 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)。

**返回值：**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

返回组内形状的集合。只读 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**返回值：**
[IShapeCollection](../../com.aspose.slides/ishapecollection)