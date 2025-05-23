---
title: ThreeDFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает объект ThreeDFormat который представляет свойства 3D-эффекта для текста. Только для чтенияIThreeDFormataspose.slides/ithreedformat.
type: docs
weight: 140
url: /ru/aspose.slides/textframeformat/threedformat/
---
## TextFrameFormat.ThreeDFormat property

Возвращает объект ThreeDFormat, который представляет свойства 3D-эффекта для текста. Только для чтения[`IThreeDFormat`](../../ithreedformat).

```csharp
public IThreeDFormat ThreeDFormat { get; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape autoShape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);

    ITextFrame textFrame = autoShape.TextFrame;

    textFrame.Text = "Aspose.Slide Test Text";

     // Установить текст transform
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUpPour;

    // Установить Extrusion
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionColor.Color = Color.Orange;
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 6;

     // Установить Contour
    textFrame.TextFrameFormat.ThreeDFormat.ContourColor.Color = Color.DarkRed;
    textFrame.TextFrameFormat.ThreeDFormat.ContourWidth = 1.5;

     // Установить глубину
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;

     // Установить Материал
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;

     // Установить освещение
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);

     // Установить тип камеры
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
}
```

### Смотрите также

* interface [IThreeDFormat](../../ithreedformat)
* class [TextFrameFormat](../../textframeformat)
* пространство имен [Aspose.Slides](../../textframeformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
