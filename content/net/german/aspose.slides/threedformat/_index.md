---
title: ThreeDFormat
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt 3-D-Eigenschaften dar.
type: docs
weight: 11180
url: /de/aspose.slides/threedformat/
---

## ThreeDFormat-Klasse

Stellt 3-D-Eigenschaften dar.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Grundschnittstelle IPresentationComponent. Nur-Lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Gibt den Typ eines unteren 3D-Fasens zurück oder setzt ihn. Nur-Lesen [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Gibt den Typ eines oberen 3D-Fasens zurück oder setzt ihn. Nur-Lesen [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Gibt die Einstellungen einer Kamera zurück oder setzt sie. Nur-Lesen [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Gibt die Farbe eines Umrisses zurück oder setzt sie. Nur-Lesen [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Gibt die Breite eines 3D-Umrisses zurück oder setzt sie. Lesen/Schreiben Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Gibt die Tiefe einer 3D-Form zurück oder setzt sie. Lesen/Schreiben Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Gibt die Farbe einer Extrusion zurück oder setzt sie. Nur-Lesen [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Gibt die Höhe eines Extrusionseffekts zurück oder setzt sie. Lesen/Schreiben Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Gibt den Typ eines Lichts zurück oder setzt ihn. Nur-Lesen [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Gibt den Typ eines Materials zurück oder setzt ihn. Lesen/Schreiben [`MaterialPresetType`](../materialpresettype). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Ruft die effektiven 3-D-Formatierungsdaten mit angewandter Vererbung ab. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine 3D-Form in einer PowerPoint-Präsentation hinzufügt.

```csharp
[C#]
// Erstelle eine Instanz der Presentation-Klasse.
using (Presentation pres = new Presentation())
{
	// Füge eine Form mit der Methode AddAutoShape hinzu
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
	// Präsentiere die Datei speichern
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man einen Gradienteneffekt auf eine 3D-Form in einer PowerPoint-Präsentation anwendet.

```csharp
[C#]
// Erstelle eine Instanz der Presentation-Klasse.
using (Presentation pres = new Presentation())
{
	// Füge eine Form mit der Methode AddAutoShape hinzu
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definiere TextFrame und seine Eigenschaften
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Konfiguriere FillFormat.FillType als FillType.Gradient und definiere die Gradienteigenschaften
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
	// Präsentiere die Datei speichern
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man einen 3D-Effekt auf Text anwendet. Um einen 3D-Text zu erstellen, ist es möglich, den WordArt-Transformationseffekt zu verwenden.

```csharp
[C#]
// Erstelle eine Instanz der Presentation-Klasse.
using (Presentation pres = new Presentation())
{
	// Füge eine Form mit der Methode AddAutoShape hinzu
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definiere TextFrame und seine Eigenschaften
    shape.TextFrame.Text = "3D Text";
	// Konfiguriere FillFormat.FillType als FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Konfiguriere Portion des TextFrames und konfiguriere die Eigenschaften von PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // Richte den "Arch Up"-WordArt-Transformationseffekt ein
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definiere ThreeDFormat-Eigenschaften des ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Präsentiere die Datei speichern
    pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IThreeDFormat](../ithreedformat)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->