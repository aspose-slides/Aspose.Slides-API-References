---
title: ThreeDFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve el objeto ThreeDFormat que representa las propiedades del efecto 3d para un texto. Solo de lectura IThreeDFormataspose.slides/ithreedformat.
type: docs
weight: 140
url: /es/aspose.slides/textframeformat/threedformat/
---

## Propiedad TextFrameFormat.ThreeDFormat

Devuelve el objeto ThreeDFormat que representa las propiedades del efecto 3d para un texto. Solo de lectura [`IThreeDFormat`](../../ithreedformat).

```csharp
public IThreeDFormat ThreeDFormat { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape autoShape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);

    ITextFrame textFrame = autoShape.TextFrame;

    textFrame.Text = "Texto de Prueba Aspose.Slide";

    // Establecer transformación de texto
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUpPour;

    // Establecer Extrusión
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionColor.Color = Color.Orange;
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 6;

    // Establecer Contorno
    textFrame.TextFrameFormat.ThreeDFormat.ContourColor.Color = Color.DarkRed;
    textFrame.TextFrameFormat.ThreeDFormat.ContourWidth = 1.5;

    // Establecer Profundidad
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;

    // Establecer Material
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;

    // Establecer Iluminación
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);

    // Establecer tipo de cámara
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
}
```

### Véase también

* interfaz [IThreeDFormat](../../ithreedformat)
* clase [TextFrameFormat](../../textframeformat)
* espacio de nombres [Aspose.Slides](../../textframeformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->