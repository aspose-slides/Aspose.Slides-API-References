---
title: ILegacyDiagram
second_title: Aspose.Slides for Java API Reference
description: Represents a legacy diagram object
type: docs
weight: 846
url: /java/com.aspose.slides/ilegacydiagram/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Represents a legacy diagram object
## Methods

| Method | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converts legacy digram to editable SmartArt object. |
| [convertToGroupShape()](#convertToGroupShape--) | Converts legacy digram to editable group shape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Converts legacy digram to editable SmartArt object. Created SmartArt object adds to parent group shape at the same position.

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - Created SmartArt object.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Converts legacy digram to editable group shape. Created GroupShape object adds to parent group shape at the same position.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.
