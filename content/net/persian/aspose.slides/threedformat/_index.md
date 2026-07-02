---
title: ThreeDFormat
second_title: Aspose.Sildes برای .NET، مرجع API
description: نمایانگر خواص 3-بعدی است.
type: docs
weight: 11490
url: /fa/aspose.slides/threedformat/
---
## ThreeDFormat کلاس

خواص 3-D را نشان می‌دهد.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## خواص

| نام | توضیح |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | اجازه می‌دهد تا رابط IPresentationComponent پایه دریافت شود. فقط‌خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | نوع برش 3D پایین را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | نوع برش 3D بالا را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | تنظیمات یک دوربین را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | رنگ یک کانتور را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | رنگ یک برآمدگی (extrusion) را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | ارتفاع اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | نوع نوری را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`MaterialPresetType`](../materialpresettype). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص شده مقایسه می‌کند. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | داده‌های قالب‌بندی 3-D مؤثر را با به‌کارگیری ارث‌بری دریافت می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### مثال‌ها

مثال زیر نشان می‌دهد که چگونه می‌توان یک شکل 3D را در ارائه PowerPoint اضافه کرد.

```csharp
[C#]
// یک شیء از کلاس Presentation ایجاد کنید.
using (Presentation pres = new Presentation())
{
	// یک شکل با استفاده از متد AddAutoShape اضافه کنید
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// تعریف TextFrame و ویژگی‌های آن
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// تعریف خواص ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// ذخیرهٔ فایل Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

مثال زیر نشان می‌دهد که چگونه می‌توان اثر گرادیان را بر شکل 3D در ارائه PowerPoint اعمال کرد.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد کنید.
using (Presentation pres = new Presentation())
{
	// یک شکل با استفاده از متد AddAutoShape اضافه کنید
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// تعریف TextFrame و ویژگی‌های آن
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// تنظیم FillFormat.FillType به FillType.Gradient و تعریف ویژگی‌های گرادیان
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// تعریف خواص ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// ذخیرهٔ فایل Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

مثال زیر نشان می‌دهد که چگونه می‌توان اثر 3D را بر متن اعمال کرد. برای ایجاد متن 3D می‌توان از اثر تبدیل WordArt استفاده کرد.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد کنید.
using (Presentation pres = new Presentation())
{
	// یک شکل با استفاده از متد AddAutoShape اضافه کنید
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// تعریف TextFrame و ویژگی‌های آن
    shape.TextFrame.Text = "3D Text";
	// تنظیم FillFormat.FillType به FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// تنظیم Portion از TextFrame و تنظیم ویژگی‌های PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // تنظیم اثر تبدیل WordArt «Arch Up»
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// تعریف خواص ThreeDFormat برای ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// ذخیرهٔ فایل Presentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* کلاس [PVIObject](../pviobject)
* اینترفیس [IThreeDFormat](../ithreedformat)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->