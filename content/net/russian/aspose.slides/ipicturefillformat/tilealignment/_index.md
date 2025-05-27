---
title: TileAlignment
second_title: Aspose.Sildes для .NET API Справочник
description: Возвращает или задает, как текстура выравнивается внутри фигуры. Эта настройка контролирует начальную точку текстурного узора и то, как он повторяется по фигуре. Чтение/запись RectangleAlignmentaspose.slides/rectanglealignment.
type: docs
weight: 130
url: /ru/aspose.slides/ipicturefillformat/tilealignment/
---

## IPictureFillFormat.TileAlignment свойство

Возвращает или задает, как текстура выравнивается внутри фигуры. Эта настройка контролирует начальную точку текстурного узора и то, как он повторяется по фигуре. Чтение/запись [`RectangleAlignment`](../../rectanglealignment).

```csharp
public RectangleAlignment TileAlignment { get; set; }
```

### Примечания

По умолчанию — TopLeft.

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Получает формат заполнения изображения фигуры
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Устанавливает режим заполнения изображения в Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Устанавливает выравнивание для плитки справа внизу
    pictureFillFormat.TileAlignment = RectangleAlignment.BottomRight;
}
```

### См. также

* enum [RectangleAlignment](../../rectanglealignment)
* interface [IPictureFillFormat](../../ipicturefillformat)
* namespace [Aspose.Slides](../../ipicturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->