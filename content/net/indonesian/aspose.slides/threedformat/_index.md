---
title: ThreeDFormat
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili properti 3-D.
type: docs
weight: 11490
url: /id/aspose.slides/threedformat/
---
## ThreeDFormat kelas

Mewakili properti 3-D.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Memungkinkan untuk mendapatkan antarmuka dasar IPresentationComponent. Hanya-baca [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Mengembalikan atau mengatur tipe bevel 3D bagian bawah. Hanya-baca [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Mengembalikan atau mengatur tipe bevel 3D bagian atas. Hanya-baca [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Mengembalikan atau mengatur pengaturan kamera. Hanya-baca [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Mengembalikan atau mengatur warna kontur. Hanya-baca [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Mengembalikan atau mengatur lebar kontur 3D. Baca/tulis Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Mengembalikan atau mengatur kedalaman bentuk 3D. Baca/tulis Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Mengembalikan atau mengatur warna ekstrusi. Hanya-baca [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Mengembalikan atau mengatur tinggi efek ekstrusi. Baca/tulis Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Mengembalikan atau mengatur tipe cahaya. Hanya-baca [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Mengembalikan atau mengatur tipe material. Baca/tulis [`MaterialPresetType`](../materialpresettype). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Membandingkan dengan objek yang ditentukan. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Mendapatkan data format 3-D yang efektif dengan pewarisan yang diterapkan. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Mengembalikan kode hash. |

### Contoh

Contoh berikut menunjukkan cara menambahkan bentuk 3D dalam Presentasi PowerPoint.

```csharp
[C#]
// Membuat instance kelas Presentation.
using (Presentation pres = new Presentation())
{
	// Menambahkan bentuk menggunakan metode AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Menetapkan TextFrame dan propertinya
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Menetapkan Properti ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Menyimpan file Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Contoh berikut menunjukkan cara menerapkan efek Gradien pada bentuk 3D dalam Presentasi PowerPoint.

```csharp
[C#]
// Membuat instance kelas Presentation.
using (Presentation pres = new Presentation())
{
	// Menambahkan bentuk menggunakan metode AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Mendefinisikan TextFrame dan propertinya
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Mengonfigurasi FillFormat.FillType sebagai FillType.Gradient dan mendefinisikan properti gradien
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Mendefinisikan Properti ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Menyimpan file Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Contoh berikut menunjukkan cara menerapkan efek 3D pada teks. Untuk membuat teks 3D dapat menggunakan efek transformasi WordArt.

```csharp
[C#]
// Membuat instance kelas Presentation.
using (Presentation pres = new Presentation())
{
	// Menambahkan bentuk menggunakan metode AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Mendefinisikan TextFrame dan propertinya
    shape.TextFrame.Text = "3D Text";
	// Mengonfigurasi FillFormat.FillType sebagai FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Mengonfigurasi Portion dari TextFrame dan mengatur properti PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // menyiapkan efek transformasi WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Mendefinisikan Properti ThreeDFormat dari ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Menyimpan file Presentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* kelas [PVIObject](../pviobject)
* antarmuka [IThreeDFormat](../ithreedformat)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->