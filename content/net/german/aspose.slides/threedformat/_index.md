---
title: ThreeDFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt 3-D Eigenschaften dar.
type: docs
weight: 11510
url: /de/aspose.slides/threedformat/
---
## ThreeDFormat Klasse

Stellt 3-D Eigenschaften dar.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur-Lese [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Gibt den Typ einer unteren 3D-Kante zurück oder legt ihn fest. Nur-Lese [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Gibt den Typ einer oberen 3D-Kante zurück oder legt ihn fest. Nur-Lese [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Gibt die Einstellungen einer Kamera zurück oder legt sie fest. Nur-Lese [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Gibt die Farbe einer Kontur zurück oder legt sie fest. Nur-Lese [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Gibt die Breite einer 3D-Kontur zurück oder legt sie fest. Lese-/Schreib-Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Gibt die Tiefe einer 3D-Form zurück oder legt sie fest. Lese-/Schreib-Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Gibt die Farbe einer Extrusion zurück oder legt sie fest. Nur-Lese [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Gibt die Höhe eines Extrusionseffekts zurück oder legt sie fest. Lese-/Schreib-Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Gibt den Typ eines Lichts zurück oder legt ihn fest. Nur-Lese [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Gibt den Typ eines Materials zurück oder legt ihn fest. Lese-/Schreib [`MaterialPresetType`](../materialpresettype). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit angegebenem Objekt. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Ermittelt effektive 3-D-Formatierungsdaten mit angewandter Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Beispiele

Das folgende Beispiel zeigt, wie man einer PowerPoint-Präsentation eine 3D-Form hinzufügt.

```csharp
[C#]
// Erstelle eine Instanz der Presentation-Klasse.
using (Presentation pres = new Presentation())
{
	// Füge eine Form mit der AddAutoShape-Methode hinzu
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Definiere TextFrame und seine Eigenschaften
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Definiere ThreeDFormat-Eigenschaften
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Speichere die Presentationsdatei
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man einen Gradient-Effekt auf eine 3D-Form in einer PowerPoint-Präsentation anwendet.

```csharp
[C#]
// Erstelle eine Instanz der Presentation-Klasse.
using (Presentation pres = new Presentation())
{
	// Füge eine Form mit der AddAutoShape-Methode hinzu
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definiere TextFrame und seine Eigenschaften
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Konfiguriere FillFormat.FillType als FillType.Gradient und definiere die Gradient-Eigenschaften
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Definiere ThreeDFormat-Eigenschaften
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Speichere die Präsentationsdatei
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man einen 3D-Effekt auf Text anwendet. Für die Erstellung von 3D-Text kann der WordArt-Transformations-Effekt verwendet werden.

```csharp
[C#]
// Erstelle eine Instanz der Presentation-Klasse.
using (Presentation pres = new Presentation())
{
	// Füge eine Form mit der AddAutoShape-Methode hinzu
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definiere TextFrame und seine Eigenschaften
    shape.TextFrame.Text = "3D Text";
	// Konfiguriere FillFormat.FillType als FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Konfiguriere Portion des TextFrames und die Eigenschaften von PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // Richte den WordArt-Transformations-Effekt "Arch Up" ein
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definiere ThreeDFormat-Eigenschaften von ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Speichere die Präsentationsdatei
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IThreeDFormat](../ithreedformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->