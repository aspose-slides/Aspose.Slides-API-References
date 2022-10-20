---
title: LegacyDiagram
second_title: Aspose.Slides for Java API Reference
description: Represents a legacy diagram object.
type: docs
weight: 266
url: /java/com.aspose.slides/legacydiagram/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Represents a legacy diagram object.
## Methods

| Method | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converts legacy digram to editable SmartArt object. |
| [convertToGroupShape()](#convertToGroupShape--) | Converts legacy digram to editable group shape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Converts legacy digram to editable SmartArt object. Created SmartArt object adds to parent group shape at the same position.

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - Created SmartArt object.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Converts legacy digram to editable group shape. Created GroupShape object adds to parent group shape at the same position.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.
