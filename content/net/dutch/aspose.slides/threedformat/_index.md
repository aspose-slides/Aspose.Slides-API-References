---
title: ThreeDFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt 3-D-eigenschappen voor.
type: docs
weight: 11510
url: /nl/aspose.slides/threedformat/
---
## ThreeDFormat klasse

Stelt 3-D-eigenschappen voor.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe om de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Geeft het type van een onderliggende 3D-afschuining terug of stelt het in. Alleen-lezen [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Geeft het type van een bovenste 3D-afschuining terug of stelt het in. Alleen-lezen [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Geeft de instellingen van een camera terug of stelt ze in. Alleen-lezen [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Geeft de kleur van een contour terug of stelt deze in. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Geeft de breedte van een 3D-contour terug of stelt deze in. Lezen/Schrijven Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Geeft de diepte van een 3D-vorm terug of stelt deze in. Lezen/Schrijven Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Geeft de kleur van een extrusie terug of stelt deze in. Alleen-lezen [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Geeft de hoogte van een extrusie-effect terug of stelt deze in. Lezen/Schrijven Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Geeft het type van een licht terug of stelt het in. Alleen-lezen [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Geeft het type van een materiaal terug of stelt het in. Lezen/Schrijven [`MaterialPresetType`](../materialpresettype). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Haalt effectieve 3-D-opmaakgegevens op met de toegepaste overerving. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Geeft hashcode terug. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe je een 3D-vorm toevoegt in een PowerPoint-presentatie.

```csharp
[C#]
// Maak een instantie van de Presentation-klasse aan.
using (Presentation pres = new Presentation())
{
	// Voeg een vorm toe met de AddAutoShape-methode
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Definieer TextFrame en de bijbehorende eigenschappen
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Definieer ThreeDFormat-eigenschappen
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Sla het Presentatie-bestand op
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Het volgende voorbeeld laat zien hoe je een gradiëntaardeffect toepast op een 3D-vorm in een PowerPoint-presentatie.

```csharp
[C#]
// Maak een instantie van de Presentation-klasse aan.
using (Presentation pres = new Presentation())
{
	// Voeg een vorm toe met de AddAutoShape-methode
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definieer TextFrame en de bijbehorende eigenschappen
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Configureer FillFormat.FillType als FillType.Gradient en definieer gradient-eigenschappen
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Definieer ThreeDFormat-eigenschappen
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Sla het Presentatie-bestand op
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Het volgende voorbeeld laat zien hoe je een 3D-effect toepast op tekst. Voor het maken van 3D-tekst kun je het WordArt-transformatieteffect gebruiken.

```csharp
[C#]
// Maak een instantie van de Presentation-klasse aan.
using (Presentation pres = new Presentation())
{
	// Voeg een vorm toe met de AddAutoShape-methode
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definieer TextFrame en de bijbehorende eigenschappen
    shape.TextFrame.Text = "3D Text";
	// Configureer FillFormat.FillType als FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Configureer Portion van TextFrame en configureer eigenschappen van PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // Stel "Arch Up" WordArt-transformatieteffect in
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definieer ThreeDFormat-eigenschappen van ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Sla het Presentatie-bestand op
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IThreeDFormat](../ithreedformat)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->