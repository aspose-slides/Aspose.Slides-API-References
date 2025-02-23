---
title: RawFrame
second_title: Aspose.Sildes for .NET API Reference
description: Returns or sets the raw shape frames properties. Read/write IShapeFrameaspose.slides/ishapeframe.
type: docs
weight: 230
url: /aspose.slides/shape/rawframe/
---

## Shape.RawFrame property

Returns or sets the raw shape frame's properties. Read/write [`IShapeFrame`](../../ishapeframe).

```csharp
public IShapeFrame RawFrame { get; set; }
```

### Examples

Code that attempts to assign undefined frame to IShape.Frame doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:

```csharp
IShape shape = ...;
shape.Frame = new ShapeFrame(float.NaN, float.NaN, float.NaN, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, float.NaN);
```

or

```csharp
slide.Shapes.AddAutoShape(ShapeType.RoundCornerRectangle, float.NaN, float.NaN, float.NaN, float.NaN);
```

Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.Frame. Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception. This applies to these use cases:

```csharp
IShape shape = ...;
shape.Frame = ...; // cannot be undefined

IShapeCollection shapes = ...;
// x, y, width, height parameters cannot be float.NaN:
{
    shapes.AddAudioFrameCD(...);
    shapes.AddAudioFrameEmbedded(...);
    shapes.AddAudioFrameLinked(...);
    shapes.AddAutoShape(...);
    shapes.AddChart(...);
    shapes.AddConnector(...);
    shapes.AddOleObjectFrame(...);
    shapes.AddPictureFrame(...);
    shapes.AddSmartArt(...);
    shapes.AddTable(...);
    shapes.AddVideoFrame(...);
    shapes.InsertAudioFrameEmbedded(...);
    shapes.InsertAudioFrameLinked(...);
    shapes.InsertAutoShape(...);
    shapes.InsertChart(...);
    shapes.InsertConnector(...);
    shapes.InsertOleObjectFrame(...);
    shapes.InsertPictureFrame(...);
    shapes.InsertTable(...);
    shapes.InsertVideoFrame(...);
}
```

But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:

```csharp
IShape shape = ...; // shape is linked to placeholder
shape.RawFrame = new ShapeFrame(float.NaN, float.NaN, 100, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
```

### See Also

* interface [IShapeFrame](../../ishapeframe)
* class [Shape](../../shape)
* namespace [Aspose.Slides](../../shape)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
