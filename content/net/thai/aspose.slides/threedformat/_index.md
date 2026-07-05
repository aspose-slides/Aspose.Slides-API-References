---
title: ThreeDFormat
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แสดงคุณสมบัติ 3-D.
type: docs
weight: 11490
url: /th/aspose.slides/threedformat/
---
## ThreeDFormat คลาส

แสดงคุณสมบัติ 3-D

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | คืนค่า หรือกำหนดประเภทของ bevel 3-D ด้านล่าง. อ่านอย่างเดียว [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | คืนค่า หรือกำหนดประเภทของ bevel 3-D ด้านบน. อ่านอย่างเดียว [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | คืนค่า หรือกำหนดการตั้งค่าของกล้อง. อ่านอย่างเดียว [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | คืนค่า หรือกำหนดสีของคอนทัวร์. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | คืนค่า หรือกำหนดความกว้างของคอนทัวร์ 3-D. อ่าน/เขียน Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | คืนค่า หรือกำหนดความลึกของรูปร่าง 3-D. อ่าน/เขียน Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | คืนค่า หรือกำหนดสีของ extrusion. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | คืนค่า หรือกำหนดความสูงของเอฟเฟกต์ extrusion. อ่าน/เขียน Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | คืนค่า หรือกำหนดประเภทของแสง. อ่านอย่างเดียว [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | คืนค่า หรือกำหนดประเภทของวัสดุ. อ่าน/เขียน [`MaterialPresetType`](../materialpresettype). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับออบเจ็กต์ที่ระบุ |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | ดึงข้อมูลการจัดรูปแบบ 3-D ที่มีผลพร้อมกับการสืบทอดที่นำไปใช้ |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | คืนค่า hash code |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปแบบ 3-D ใน PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation.
using (Presentation pres = new Presentation())
{
	// เพิ่มรูปทรงโดยใช้เมธอด AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// กำหนด TextFrame และคุณสมบัติของมัน
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

ตัวอย่างต่อไปนี้แสดงวิธีการใช้เอฟเฟกต์ Gradient กับรูปแบบ 3-D ใน PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation.
using (Presentation pres = new Presentation())
{
	// เพิ่มรูปทรงโดยใช้เมธอด AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// กำหนด TextFrame และคุณสมบัติของมัน
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// ตั้งค่า FillFormat.FillType เป็น FillType.Gradient และกำหนดคุณสมบัติของ gradient
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

ตัวอย่างต่อไปนี้แสดงวิธีการใช้เอฟเฟกต์ 3-D กับข้อความ. สำหรับการสร้างข้อความ 3-D สามารถใช้เอฟเฟกต์การแปลง WordArt.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation.
using (Presentation pres = new Presentation())
{
	// เพิ่มรูปทรงโดยใช้เมธอด AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// กำหนด TextFrame และคุณสมบัติของมัน
    shape.TextFrame.Text = "3D Text";
	// ตั้งค่า FillFormat.FillType เป็น FillType.NoFill
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
    // ตั้งค่าเอฟเฟ็กต์การแปลง WordArt "Arch Up"
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