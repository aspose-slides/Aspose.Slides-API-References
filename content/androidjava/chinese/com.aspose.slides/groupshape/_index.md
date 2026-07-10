---
title: GroupShape
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示幻灯片上的一组形状。
type: docs
url: /zh/com.aspose.slides/groupshape/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**所有实现的接口：**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

表示幻灯片上的一组形状。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 返回包含形状线条格式属性的 LineFormat 对象。 |
| [getGroupShapeLock()](#getGroupShapeLock--) | 返回形状的锁。 |
| [getShapes()](#getShapes--) | 返回组内形状的集合。 |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


返回包含形状线条格式属性的 LineFormat 对象。注意：对于 GroupShape 对象返回 null，因为它们没有线条属性。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


返回形状的锁。只读 [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)。

**返回：**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


返回组内形状的集合。只读 [IShapeCollection](../../com.aspose.slides/ishapecollection)。

**返回：**
[IShapeCollection](../../com.aspose.slides/ishapecollection)