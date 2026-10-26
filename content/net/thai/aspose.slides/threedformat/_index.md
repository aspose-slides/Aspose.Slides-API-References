---
title: ThreeDFormat
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงคุณสมบัติ 3 มิติ.
type: docs
weight: 11490
url: /th/aspose.slides/threedformat/
---
## ThreeDFormat คลาส

Represents 3-D properties.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Returns or sets the type of a bottom 3D bevel. อ่านอย่างเดียว [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Returns or sets the type of a top 3D bevel. อ่านอย่างเดียว [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Returns or sets the settings of a camera. อ่านอย่างเดียว [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Returns or sets the color of a contour. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Returns or sets the width of a 3D contour. อ่าน/เขียน Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Returns or sets the depth of a 3D shape. อ่าน/เขียน Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Returns or sets the color of an extrusion. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Returns or sets the height of an extrusion effect. อ่าน/เขียน Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Returns or sets the type of a light. อ่านอย่างเดียว [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Returns or sets the type of a material. อ่าน/เขียน [`MaterialPresetType`](../materialpresettype). |

## เมธอด

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับวัตถุที่ระบุ. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Gets effective 3-D formatting data with the inheritance applied. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |

### ตัวอย่าง

The following example shows how to add 3D shape in PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation.
using (Presentation pres = new Presentation())
{
	// เพิ่มรูปร่างโดยใช้เมธอด AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// กำหนด TextFrame และคุณสมบัติต่าง ๆ ของมัน
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// กำหนดคุณสมบัติของ ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// บันทึกไฟล์ Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation.
using (Presentation pres = new Presentation())
{
	// เพิ่มรูปร่างโดยใช้เมธอด AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// กำหนด TextFrame และคุณสมบัติต่าง ๆ ของมัน
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// กำหนด FillFormat.FillType เป็น FillType.Gradient และกำหนดคุณสมบัติของเกรเดียนต์
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// กำหนดคุณสมบัติของ ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// บันทึกไฟล์ Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation.
using (Presentation pres = new Presentation())
{
	// เพิ่มรูปร่างโดยใช้เมธอด AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// กำหนด TextFrame และคุณสมบัติต่าง ๆ ของมัน
    shape.TextFrame.Text = "3D Text";
	// กำหนด FillFormat.FillType เป็น FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// กำหนด Portion ของ TextFrame และตั้งค่าคุณสมบัติของ PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // ตั้งค่าเอฟเฟกต์แปลง WordArt แบบ "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// กำหนดคุณสมบัติของ ThreeDFormat ของ ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// บันทึกไฟล์ Presentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject)
* อินเทอร์เฟซ [IThreeDFormat](../ithreedformat)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->