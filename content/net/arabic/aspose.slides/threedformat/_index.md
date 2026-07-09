---
title: ThreeDFormat
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل خصائص ثلاثية الأبعاد.
type: docs
weight: 11490
url: /ar/aspose.slides/threedformat/
---
## ThreeDFormat فئة

Represents 3-D properties.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | يسمح بالحصول على الواجهة الأساسية IPresentationComponent. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | يرجع أو يحدد نوع الحافة السفلية ثلاثية الأبعاد. قراءة فقط [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | يرجع أو يحدد نوع الحافة العلوية ثلاثية الأبعاد. قراءة فقط [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | يرجع أو يحدد إعدادات الكاميرا. قراءة فقط [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | يرجع أو يحدد لون الحد. قراءة فقط [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | يرجع أو يحدد عرض الحد ثلاثي الأبعاد. قراءة/كتابة Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | يرجع أو يحدد عمق الشكل ثلاثي الأبعاد. قراءة/كتابة Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | يرجع أو يحدد لون البثق. قراءة فقط [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | يرجع أو يحدد ارتفاع تأثير البثق. قراءة/كتابة Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | يرجع أو يحدد نوع الضوء. قراءة فقط [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | يرجع أو يحدد نوع المادة. قراءة/كتابة [`MaterialPresetType`](../materialpresettype). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | يقارن مع الكائن المحدد. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | يحصل على بيانات تنسيق ثلاثية الأبعاد الفعالة مع تطبيق الوراثة. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | يرجع رمز التجزئة. |

### أمثلة

يُظهر المثال التالي كيفية إضافة شكل ثلاثي الأبعاد في عرض PowerPoint.

```csharp
[C#]
// إنشاء مثال من فئة Presentation.
using (Presentation pres = new Presentation())
{
	// إضافة شكل باستخدام طريقة AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// تحديد TextFrame وخصائصه
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// تحديد خصائص ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// حفظ ملف Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

يُظهر المثال التالي كيفية تطبيق تأثير التدرج على شكل ثلاثي الأبعاد في عرض PowerPoint.

```csharp
[C#]
// إنشاء مثال من فئة Presentation.
using (Presentation pres = new Presentation())
{
	// إضافة شكل باستخدام طريقة AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// تعريف TextFrame وخصائصه
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// تكوين FillFormat.FillType كـ FillType.Gradient وتعريف خصائص التدرج
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// تعريف خصائص ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// حفظ ملف Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

يُظهر المثال التالي كيفية تطبيق تأثير ثلاثي الأبعاد على النص. لإنشاء نص ثلاثي الأبعاد يمكن استخدام تأثير التحويل WordArt.

```csharp
[C#]
// إنشاء مثال من فئة Presentation.
using (Presentation pres = new Presentation())
{
	// إضافة شكل باستخدام طريقة AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// تعريف TextFrame وخصائصه
    shape.TextFrame.Text = "3D Text";
	// تكوين FillFormat.FillType كـ FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// تكوين جزء من TextFrame وتكوين خصائص PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // إعداد تأثير التحويل "Arch Up" لـ WordArt
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// تعريف خصائص ThreeDFormat لـ ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// حفظ ملف Presentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* فئة [PVIObject](../pviobject)
* واجهة [IThreeDFormat](../ithreedformat)
* مساحة اسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->