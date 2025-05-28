---
title: ThreeDFormat
second_title: Справка по API Aspose.Slides для .NET
description: Представляет 3-D свойства.
type: docs
weight: 11180
url: /ru/aspose.slides/threedformat/
---

## Класс ThreeDFormat

Представляет 3-D свойства.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Возвращает или устанавливает тип нижнего 3D фаски. Только для чтения [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Возвращает или устанавливает тип верхнего 3D фаски. Только для чтения [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Возвращает или устанавливает настройки камеры. Только для чтения [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Возвращает или устанавливает цвет контура. Только для чтения [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Возвращает или устанавливает ширину 3D контура. Чтение/запись Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Возвращает или устанавливает глубину 3D фигуры. Чтение/запись Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Возвращает или устанавливает цвет экструзии. Только для чтения [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Возвращает или устанавливает высоту эффекта экструзии. Чтение/запись Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Возвращает или устанавливает тип света. Только для чтения [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Возвращает или устанавливает тип материала. Чтение/запись [`MaterialPresetType`](../materialpresettype). |

## Методы

| Название | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Получает эффективные данные 3-D форматирования с примененным наследованием. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Примеры

Следующий пример демонстрирует, как добавить 3D фигуру в презентацию PowerPoint.

```csharp
[C#]
// Создать экземпляр класса Presentation.
using (Presentation pres = new Presentation())
{
	// Добавить фигуру с помощью метода AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Определить TextFrame и его свойства
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Определить свойства ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Сохранить файл презентации
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Следующий пример демонстрирует, как применить градиентный эффект к 3D фигуре в презентации PowerPoint.

```csharp
[C#]
// Создать экземпляр класса Presentation.
using (Presentation pres = new Presentation())
{
	// Добавить фигуру с помощью метода AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Определить TextFrame и его свойства
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Настроить FillFormat.FillType как FillType.Gradient и определить градиентные свойства
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Определить свойства ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Сохранить файл презентации
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Следующий пример демонстрирует, как применить 3D эффект к тексту. Для создания 3D текста возможно использовать эффект трансформации WordArt.

```csharp
[C#]
// Создать экземпляр класса Presentation.
using (Presentation pres = new Presentation())
{
	// Добавить фигуру с помощью метода AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Определить TextFrame и его свойства
    shape.TextFrame.Text = "3D Text";
	// Настроить FillFormat.FillType как FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Настроить Portion TextFrame и задать свойства PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // настроить эффект трансформации WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Определить свойства ThreeDFormat ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Сохранить файл презентации
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IThreeDFormat](../ithreedformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->