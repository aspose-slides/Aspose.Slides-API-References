---
title: ThreeDFormat
second_title: Aspose.Sildes .NET API hivatkozás
description: 3-D tulajdonságokat képviseli.
type: docs
weight: 11490
url: /hu/aspose.slides/threedformat/
---
## ThreeDFormat osztály

A 3-D tulajdonságokat képviseli.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi az IPresentationComponent alap interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Visszaadja vagy beállítja az alsó 3D rézsút típusát. Csak olvasható [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Visszaadja vagy beállítja a felső 3D rézsút típusát. Csak olvasható [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Visszaadja vagy beállítja a kamera beállításait. Csak olvasható [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Visszaadja vagy beállítja egy körvonal színét. Csak olvasható [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Visszaadja vagy beállítja egy 3D körvonal szélességét. Olvasás/írás Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Visszaadja vagy beállítja egy 3D alak mélységét. Olvasás/írás Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Visszaadja vagy beállítja egy extrudálás színét. Csak olvasható [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Visszaadja vagy beállítja egy extrudálási effektus magasságát. Olvasás/írás Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Visszaadja vagy beállítja egy fény típusát. Csak olvasható [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Visszaadja vagy beállítja egy anyag típusát. Olvasás/írás [`MaterialPresetType`](../materialpresettype). |

## Módszerek

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Lekéri a tényleges 3-D formázási adatokat az öröklődés alkalmazásával. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Példák

Az alábbi példa bemutatja, hogyan adhatunk hozzá 3D alakzatot egy PowerPoint bemutatóhoz.

```csharp
[C#]
// Hozzon létre egy Presentation osztály példányt.
using (Presentation pres = new Presentation())
{
	// Adj hozzá egy alakzatot az AddAutoShape metódussal
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Határozza meg a TextFrame-et és annak tulajdonságait
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Határozza meg a ThreeDFormat tulajdonságait
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Mentse a Presentation fájlt
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Az alábbi példa bemutatja, hogyan alkalmazhatunk Gradient effektet egy 3D alakzatra egy PowerPoint bemutatóban.

```csharp
[C#]
// Hozzon létre egy Presentation osztály példányt.
using (Presentation pres = new Presentation())
{
	// Adj hozzá egy alakzatot az AddAutoShape metódussal
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Határozza meg a TextFrame-et és annak tulajdonságait
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Állítsa be a FillFormat.FillType értékét FillType.Gradient-re, és határozza meg a gradient tulajdonságait
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Határozza meg a ThreeDFormat tulajdonságait
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Mentse a Presentation fájlt
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Az alábbi példa bemutatja, hogyan alkalmazhatunk 3D effektet szövegre. 3D szöveg létrehozásához a WordArt transzformációs effektust lehet használni.

```csharp
[C#]
// Hozzon létre egy Presentation osztály példányt.
using (Presentation pres = new Presentation())
{
	// Adj hozzá egy alakzatot az AddAutoShape metódussal
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Határozza meg a TextFrame-et és annak tulajdonságait
    shape.TextFrame.Text = "3D Text";
	// Állítsa be a FillFormat.FillType értékét FillType.NoFill-re
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Konfigurálja a TextFrame részét és állítsa be a PortionFormat tulajdonságait
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // állítsa be a "Arch Up" WordArt transzformációs effektust
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definiálja az ITextFrame ThreeDFormat tulajdonságait
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Mentse a Presentation fájlt
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IThreeDFormat](../ithreedformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->