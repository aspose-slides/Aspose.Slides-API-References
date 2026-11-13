---
title: ThreeDFormat
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر ویژگی‌های 3-بعدی است.
type: docs
weight: 11510
url: /fa/aspose.slides/threedformat/
---
## کلاس ThreeDFormat

نمایش می‌دهد ویژگی‌های 3-بعدی.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | اجازه دریافت رابط IPresentationComponent پایه. فقط خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | بازگرداندن یا تنظیم نوع برجستگی 3-بعدی پایین. فقط خواندنی [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | بازگرداندن یا تنظیم نوع برجستگی 3-بعدی بالا. فقط خواندنی [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | بازگرداندن یا تنظیم تنظیمات دوربین. فقط خواندنی [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | بازگرداندن یا تنظیم رنگ خطوط دور. فقط خواندنی [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | بازگرداندن یا تنظیم عرض خطوط دور 3-بعدی. قابل خواندن و نوشتن Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | بازگرداندن یا تنظیم عمق یک اشکال 3-بعدی. قابل خواندن و نوشتن Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | بازگرداندن یا تنظیم رنگ بیرون‌زدگی. فقط خواندنی [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | بازگرداندن یا تنظیم ارتفاع اثر بیرون‌زدگی. قابل خواندن و نوشتن Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | بازگرداندن یا تنظیم نوع نور. فقط خواندنی [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | بازگرداندن یا تنظیم نوع ماده. قابل خواندن و نوشتن [`MaterialPresetType`](../materialpresettype). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | مقایسه با شیء مشخص شده. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | دریافت داده‌های قالب‌بندی مؤثر 3-بعدی با اعمال وراثت. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | بازگرداندن کد هش. |

### مثال‌ها

مثال زیر نشان می‌دهد چطور یک شکل 3-بعدی را در ارائه PowerPoint اضافه کنیم.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد کنید.
using (Presentation pres = new Presentation())
{
	// یک شکل را با استفاده از متد AddAutoShape اضافه کنید
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// تعریف TextFrame و ویژگی‌های آن
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// تعریف خصوصیات ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// فایل Presentation را ذخیره کنید
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

مثال زیر نشان می‌دهد چطور اثر Gradient را بر شکل 3-بعدی در ارائه PowerPoint اعمال کنیم.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد کنید.
using (Presentation pres = new Presentation())
{
	// یک شکل را با استفاده از متد AddAutoShape اضافه کنید
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// تعریف TextFrame و ویژگی‌های آن
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// پیکربندی FillFormat.FillType به عنوان FillType.Gradient و تعریف ویژگی‌های گرادیان
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// تعریف خصوصیات ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// ذخیره فایل Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

مثال زیر نشان می‌دهد چطور اثر 3-بعدی را بر متن اعمال کنیم. برای ایجاد متن 3-بعدی می‌توان از اثر تبدیل WordArt استفاده کرد.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد کنید.
using (Presentation pres = new Presentation())
{
	// یک شکل را با استفاده از متد AddAutoShape اضافه کنید
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// تعریف TextFrame و ویژگی‌های آن
    shape.TextFrame.Text = "3D Text";
	// پیکربندی FillFormat.FillType به عنوان FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// پیکربندی Portion از TextFrame و تنظیم ویژگی‌های PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // تنظیم اثر تبدیل WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// تعریف خصوصیات ThreeDFormat از ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// ذخیره فایل Presentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### همچنین ببینید

* کلاس [PVIObject](../pviobject)
* رابط [IThreeDFormat](../ithreedformat)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->