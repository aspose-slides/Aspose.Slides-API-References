---
title: ThreeDFormat
second_title: Aspose.Sildes pour la référence API .NET
description: Retourne l'objet ThreeDFormat qui représente les propriétés d'effet 3d pour un texte. En lecture seule IThreeDFormataspose.slides/ithreedformat.
type: docs
weight: 140
url: /fr/aspose.slides/itextframeformat/threedformat/
---

## ITextFrameFormat.ThreeDFormat propriété

Retourne l'objet ThreeDFormat qui représente les propriétés d'effet 3d pour un texte. En lecture seule [`IThreeDFormat`](../../ithreedformat).

```csharp
public IThreeDFormat ThreeDFormat { get; }
```

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape autoShape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);

    ITextFrame textFrame = autoShape.TextFrame;

    textFrame.Text = "Aspose.Slide Test Text";

    // Définir la transformation du texte
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUpPour;

    // Définir l'extrusion
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionColor.Color = Color.Orange;
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 6;

    // Définir le contour
    textFrame.TextFrameFormat.ThreeDFormat.ContourColor.Color = Color.DarkRed;
    textFrame.TextFrameFormat.ThreeDFormat.ContourWidth = 1.5;

    // Définir la profondeur
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;

    // Définir le matériau
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;

    // Définir l'éclairage
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);

    // Définir le type de caméra
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
}
```

### Voir aussi

* interface [IThreeDFormat](../../ithreedformat)
* interface [ITextFrameFormat](../../itextframeformat)
* namespace [Aspose.Slides](../../itextframeformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->