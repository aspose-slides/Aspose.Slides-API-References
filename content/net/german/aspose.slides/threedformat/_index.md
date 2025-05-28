---
title: ThreeDFormat
second_title: Aspose.Slides für .NET API-Referenz
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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf das Basis-IPresentationComponent-Interface. Nur-Lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Gibt den Typ eines unteren 3D-Facetten an oder setzt ihn. Nur-Lesen [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Gibt den Typ einer oberen 3D-Facette an oder setzt ihn. Nur-Lesen [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Gibt die Einstellungen einer Kamera an oder setzt sie. Nur-Lesen [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Gibt die Farbe eines Umrisses an oder setzt sie. Nur-Lesen [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Gibt die Breite eines 3D-Umrisses an oder setzt sie. Lesen/Schreiben Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Gibt die Tiefe einer 3D-Form an oder setzt sie. Lesen/Schreiben Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Gibt die Farbe einer Extrusion an oder setzt sie. Nur-Lesen [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Gibt die Höhe eines Extrusionseffekts an oder setzt sie. Lesen/Schreiben Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Gibt den Typ eines Lichts an oder setzt ihn. Nur-Lesen [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Gibt den Typ eines Materials an oder setzt ihn. Lesen/Schreiben [`MaterialPresetType`](../materialpresettype). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Holt die wirksamen 3-D-Formatierungsdaten mit der angewendeten Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine 3D-Form in einer PowerPoint-Präsentation hinzufügt.

```csharp
[C#]
// Erstellen Sie eine Instanz der Präsentationsklasse.
using (Presentation pres = new Presentation())
{
	// Fügen Sie eine Form mit der Methode AddAutoShape hinzu
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Definieren Sie TextFrame und dessen Eigenschaften
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Definieren Sie ThreeDFormat-Eigenschaften
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Speichern Sie die Präsentationsdatei
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man einen Verlaufs-Effekt auf eine 3D-Form in einer PowerPoint-Präsentation anwendet.

```csharp
[C#]
// Erstellen Sie eine Instanz der Präsentationsklasse.
using (Presentation pres = new Presentation())
{
	// Fügen Sie eine Form mit der Methode AddAutoShape hinzu
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definieren Sie TextFrame und dessen Eigenschaften
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Konfigurieren Sie FillFormat.FillType als FillType.Gradient und definieren Sie die Verlaufseigenschaften
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Definieren Sie ThreeDFormat-Eigenschaften
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Speichern Sie die Präsentationsdatei
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man einen 3D-Effekt auf Text anwendet. Für die Erstellung eines 3D-Texts ist es möglich, den WordArt-Transformations-Effekt zu verwenden.

```csharp
[C#]
// Erstellen Sie eine Instanz der Präsentationsklasse.
using (Presentation pres = new Presentation())
{
	// Fügen Sie eine Form mit der Methode AddAutoShape hinzu
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definieren Sie TextFrame und dessen Eigenschaften
    shape.TextFrame.Text = "3D Text";
	// Konfigurieren Sie FillFormat.FillType als FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Konfigurieren Sie das Portion von TextFrame und die Eigenschaften des PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // Einrichtung des "Arch Up" WordArt-Transformations-Effekts
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definieren Sie die ThreeDFormat-Eigenschaften von ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Speichern Sie die Präsentationsdatei
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IThreeDFormat](../ithreedformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->