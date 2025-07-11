---
title: AddGroupShape
second_title: Aspose.Sildes for .NET API Reference
description: Creates a new empty group shape and adds it to the end of the shape collection. The groups frame will automatically adjust to fit any shapes added to it.
type: docs
weight: 130
url: /aspose.slides/shapecollection/addgroupshape/
---

## AddGroupShape() {#addgroupshape}

Creates a new empty group shape and adds it to the end of the shape collection. The group’s frame will automatically adjust to fit any shapes added to it.

```csharp
public IGroupShape AddGroupShape()
```

### Return Value

The newly created [`IGroupShape`](../../igroupshape).

### Examples

The following example shows how to add a group shape to a slide of PowerPoint Presentation.

```csharp
[C#]
// Instantiate Prseetation class
using (Presentation pres = new Presentation())
{
    // Get the first slide
    ISlide sld = pres.Slides[0];
    // Accessing the shape collection of slides
    IShapeCollection slideShapes = sld.Shapes;
    // Adding a group shape to the slide
    IGroupShape groupShape = slideShapes.AddGroupShape();
    // Adding shapes inside added group shape
    groupShape.Shapes.AddAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
    groupShape.Shapes.AddAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
    groupShape.Shapes.AddAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
    groupShape.Shapes.AddAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
    // Adding group shape frame
    groupShape.Frame = new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0);
    // Write the PPTX file to disk
    pres.Save("GroupShape_out.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IGroupShape](../../igroupshape)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddGroupShape(ISvgImage, float, float, float, float) {#addgroupshape_1}

Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection.

```csharp
public IGroupShape AddGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | ISvgImage | The [`ISvgImage`](../../isvgimage) containing vector content to convert into shapes. |
| x | Single | The x-coordinate of the group’s frame, in points. |
| y | Single | The y-coordinate of the group’s frame, in points. |
| width | Single | The width of the group’s frame, in points. |
| height | Single | The height of the group’s frame, in points. |

### Return Value

The newly created [`IGroupShape`](../../igroupshape).

### See Also

* interface [IGroupShape](../../igroupshape)
* interface [ISvgImage](../../isvgimage)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
