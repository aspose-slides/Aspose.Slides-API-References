---
title: ThreeDFormat
second_title: Aspose.Sildes for .NET API Reference
description: Represents 3-D properties.
type: docs
weight: 10960
url: /aspose.slides/threedformat/
---

## ThreeDFormat class

Represents 3-D properties.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Returns or sets the type of a bottom 3D bevel. Read-only [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Returns or sets the type of a top 3D bevel. Read-only [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Returns or sets the settings of a camera. Read-only [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Returns or sets the color of a contour. Read-only [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Returns or sets the width of a 3D contour. Read/write Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Returns or sets the depth of a 3D shape. Read/write Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Returns or sets the color of an extrusion. Read-only [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Returns or sets the height of an extrusion effect. Read/write Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Returns or sets the type of a light. Read-only [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Returns or sets the type of a material. Read/write [`MaterialPresetType`](../materialpresettype). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compares with specified object. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Gets effective 3-D formatting data with the inheritance applied. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |

### Examples

The following example shows how to add 3D shape in PowerPoint Presentation.

```csharp
[C#]
// Create an instance of Presentation class.
using (Presentation pres = new Presentation())
{
	// Add a shape using AddAutoShape method
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Define TextFrame and its properties
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Define ThreeDFormat Properties
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Save the Presentation file
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.

```csharp
[C#]
// Create an instance of Presentation class.
using (Presentation pres = new Presentation())
{
	// Add a shape using AddAutoShape method
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Define TextFrame and its properties
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Configure FillFormat.FillType as FillType.Gradient and define gradient properties
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Define ThreeDFormat Properties
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Save the Presentation file
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.

```csharp
[C#]
// Create an instance of Presentation class.
using (Presentation pres = new Presentation())
{
	// Add a shape using AddAutoShape method
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Define TextFrame and its properties
    shape.TextFrame.Text = "3D Text";
	// Configure FillFormat.FillType as FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Configure Portion of TextFrame and configure properties of PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // setup "Arch Up" WordArt transform effect
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Define ThreeDFormat Properties of ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Save the Presentation file
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [PVIObject](../pviobject)
* interface [IThreeDFormat](../ithreedformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
