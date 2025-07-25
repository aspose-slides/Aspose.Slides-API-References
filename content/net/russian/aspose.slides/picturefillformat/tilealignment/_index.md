---
title: TileAlignment
second_title: Aspose.Sildes для .NET API Reference
description: Возвращает или задает, как текстура выровнена внутри фигуры. Эта настройка контролирует начальную точку текстурного рисунка и то, как он повторяется по всей фигуре. Чтение/запись RectangleAlignmentaspose.slides/rectanglealignment.
type: docs
weight: 120
url: /ru/aspose.slides/picturefillformat/tilealignment/
---

## PictureFillFormat.TileAlignment property

Возвращает или задает, как текстура выровнена внутри фигуры. Эта настройка контролирует начальную точку текстурного рисунка и то, как он повторяется по всей фигуре. Чтение/запись [`RectangleAlignment`](../../rectanglealignment).

```csharp
public RectangleAlignment TileAlignment { get; set; }
```

### Remarks

По умолчанию - TopLeft.

### Examples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Получает формат заливки изображения фигуры
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Устанавливает режим заливки изображения в Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Устанавливает выравнивание для плитки в правый нижний угол
    pictureFillFormat.TileAlignment = RectangleAlignment.BottomRight;
}
```

### See Also

* enum [RectangleAlignment](../../rectanglealignment)
* class [PictureFillFormat](../../picturefillformat)
* namespace [Aspose.Slides](../../picturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->