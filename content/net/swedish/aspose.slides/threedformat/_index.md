---
title: ThreeDFormat
second_title: Aspose.Sildes för .NET API-referens
description: Representerar 3-D egenskaper.
type: docs
weight: 11470
url: /sv/aspose.slides/threedformat/
---
## ThreeDFormat klass

Representerar 3-D-egenskaper.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Skrivskyddad [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Returnerar eller anger typen av en botten-3D-fasett. Skrivskyddad [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Returnerar eller anger typen av en övre 3D-fasett. Skrivskyddad [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Returnerar eller anger inställningarna för en kamera. Skrivskyddad [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Returnerar eller anger färgen på en kontur. Skrivskyddad [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Returnerar eller anger bredden på en 3D-kontur. Läs/skriv Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Returnerar eller anger djupet på en 3D-form. Läs/skriv Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Returnerar eller anger färgen på en extrudering. Skrivskyddad [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Returnerar eller anger höjden på en extruderings-effekt. Läs/skriv Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Returnerar eller anger typen av ett ljus. Skrivskyddad [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Returnerar eller anger typen av ett material. Läs/skriv [`MaterialPresetType`](../materialpresettype). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med angivet objekt. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Hämtar effektiva 3-D-formateringsdata med arv tillämpat. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hash-kod. |

### Exempel

Följande exempel visar hur man lägger till en 3D-form i en PowerPoint-presentation.

```csharp
[C#]
// Skapa en instans av Presentation-klassen.
using (Presentation pres = new Presentation())
{
	// Lägg till en form med metoden AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Definiera TextFrame och dess egenskaper
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Definiera ThreeDFormat-egenskaper
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Spara presentationsfilen
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Följande exempel visar hur man tillämpar en gradient-effekt på en 3D-form i en PowerPoint-presentation.

```csharp
[C#]
// Skapa en instans av Presentation-klassen.
using (Presentation pres = new Presentation())
{
	// Lägg till en form med metoden AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definiera TextFrame och dess egenskaper
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Konfigurera FillFormat.FillType som FillType.Gradient och definiera gradientegenskaper
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Definiera ThreeDFormat-egenskaper
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Spara presentationsfilen
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Följande exempel visar hur man applicerar 3D-effekt på text. För att skapa 3D-text är det möjligt att använda WordArt-transform-effekt.

```csharp
[C#]
// Skapa en instans av Presentation-klassen.
using (Presentation pres = new Presentation())
{
	// Lägg till en form med metoden AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definiera TextFrame och dess egenskaper
    shape.TextFrame.Text = "3D Text";
	// Konfigurera FillFormat.FillType som FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Konfigurera Portion av TextFrame och konfigurera egenskaperna för PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // ställ in "Arch Up" WordArt transformeffekt
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definiera ThreeDFormat-egenskaper för ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Spara presentationsfilen
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Se också

* klass [PVIObject](../pviobject)
* gränssnitt [IThreeDFormat](../ithreedformat)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->