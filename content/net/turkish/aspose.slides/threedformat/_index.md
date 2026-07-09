---
title: ThreeDFormat
second_title: Aspose.Sildes for .NET API Referansı
description: 3-D özellikleri temsil eder.
type: docs
weight: 11490
url: /tr/aspose.slides/threedformat/
---
## ThreeDFormat sınıfı

3-D özelliklerini temsil eder.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Salt okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Alt 3D köşe tipini döndürür veya ayarlar. Salt okunur [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Üst 3D köşe tipini döndürür veya ayarlar. Salt okunur [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Kamera ayarlarını döndürür veya ayarlar. Salt okunur [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Kontürün rengini döndürür veya ayarlar. Salt okunur [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | 3D kontürün genişliğini döndürür veya ayarlar. Okunabilir/Yazılabilir Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | 3D şeklin derinliğini döndürür veya ayarlar. Okunabilir/Yazılabilir Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Ekstrüzyonun rengini döndürür veya ayarlar. Salt okunur [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Ekstrüzyon etkisinin yüksekliğini döndürür veya ayarlar. Okunabilir/Yazılabilir Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Işığın tipini döndürür veya ayarlar. Salt okunur [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Malzemenin tipini döndürür veya ayarlar. Okunabilir/Yazılabilir [`MaterialPresetType`](../materialpresettype). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Uygulanan kalıtımla birlikte etkili 3-D biçimlendirme verilerini alır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodu döndürür. |

### Örnekler

Aşağıdaki örnek, PowerPoint Sunumunda 3D şekil eklemeyi gösterir.

```csharp
[C#]
// Presentation sınıfının bir örneğini oluştur.
using (Presentation pres = new Presentation())
{
	// AddAutoShape yöntemiyle bir şekil ekle
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// TextFrame ve özelliklerini tanımla
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// ThreeDFormat özelliklerini tanımla
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation dosyasını kaydet
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Aşağıdaki örnek, PowerPoint Sunumunda 3D şekle Degrade etkisi uygulamayı gösterir.

```csharp
[C#]
// Presentation sınıfının bir örneğini oluştur.
using (Presentation pres = new Presentation())
{
	// AddAutoShape yöntemiyle bir şekil ekle
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame'i ve özelliklerini tanımla
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// FillFormat.FillType'ı FillType.Gradient olarak yapılandır ve degrade özelliklerini tanımla
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// ThreeDFormat özelliklerini tanımla
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Presentation dosyasını kaydet
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Aşağıdaki örnek, metne 3D etkisi uygulamayı gösterir. 3D metin oluşturmak için WordArt dönüştürme etkisi kullanılabilir.

```csharp
[C#]
// Presentation sınıfının bir örneğini oluştur.
using (Presentation pres = new Presentation())
{
	// AddAutoShape yöntemiyle bir şekil ekle
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// TextFrame'i ve özelliklerini tanımla
    shape.TextFrame.Text = "3D Text";
	// FillFormat.FillType'ı FillType.NoFill olarak yapılandır
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// TextFrame'in Portion'ını yapılandır ve PortionFormat özelliklerini ayarla
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // "Arch Up" WordArt dönüşüm etkisini ayarla
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// ITextFrame'in ThreeDFormat özelliklerini tanımla
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Presentation dosyasını kaydet
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Ayrıca Bakınız

* sınıf [PVIObject](../pviobject)
* arayüz [IThreeDFormat](../ithreedformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->