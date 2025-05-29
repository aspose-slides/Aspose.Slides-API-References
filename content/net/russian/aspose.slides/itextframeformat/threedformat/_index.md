---
title: ThreeDFormat
second_title: Aspose.Slides для .NET API Справочник
description: Возвращает объект ThreeDFormat, который представляет свойства 3d эффектов для текста. Только для чтения IThreeDFormataspose.slides/ithreedformat.
type: docs
weight: 140
url: /ru/aspose.slides/itextframeformat/threedformat/
---

## Свойство ITextFrameFormat.ThreeDFormat

Возвращает объект ThreeDFormat, который представляет свойства 3d эффектов для текста. Только для чтения [`IThreeDFormat`](../../ithreedformat).

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

    // Устанавливаем преобразование текста
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUpPour;

    // Устанавливаем экструзию
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionColor.Color = Color.Orange;
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 6;

    // Устанавливаем контур
    textFrame.TextFrameFormat.ThreeDFormat.ContourColor.Color = Color.DarkRed;
    textFrame.TextFrameFormat.ThreeDFormat.ContourWidth = 1.5;

    // Устанавливаем глубину
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;

    // Устанавливаем материал
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;

    // Устанавливаем освещение
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);

    // Устанавливаем тип камеры
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
}
```

### См. также

* интерфейс [IThreeDFormat](../../ithreedformat)
* интерфейс [ITextFrameFormat](../../itextframeformat)
* пространство имен [Aspose.Slides](../../itextframeformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->