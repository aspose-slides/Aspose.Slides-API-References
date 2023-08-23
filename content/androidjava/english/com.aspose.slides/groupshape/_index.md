---
title: GroupShape
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a group of shapes on a slide.
type: docs
url: /com.aspose.slides/groupshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**All Implemented Interfaces:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Represents a group of shapes on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat object that contains line formatting properties for a shape. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Returns shape's locks. |
| [getShapes()](#getShapes--) | Returns the collection of shapes inside the group. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Returns the LineFormat object that contains line formatting properties for a shape. Note: Returns null for GroupShape objects because they don't have line properties. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Returns shape's locks. Read-only [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Returns:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Returns the collection of shapes inside the group. Read-only [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returns:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
