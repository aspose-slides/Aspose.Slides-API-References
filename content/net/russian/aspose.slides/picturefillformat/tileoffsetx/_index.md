---
title: TileOffsetX
second_title: Aspose.Sildes для .NET API Справочник
description: Возвращает или устанавливает горизонтальный сдвиг текстуры от начала формы в пунктах. Положительное значение смещает текстуру вправо, в то время как отрицательное значение смещает её влево. Чтение/запись Single.
type: docs
weight: 140
url: /ru/aspose.slides/picturefillformat/tileoffsetx/
---

## PictureFillFormat.TileOffsetX свойство

Возвращает или устанавливает горизонтальный сдвиг текстуры от начала формы в пунктах. Положительное значение смещает текстуру вправо, в то время как отрицательное значение смещает её влево. Чтение/запись Single.

```csharp
public float TileOffsetX { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Получает формат заполнения картинки формы
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Устанавливает режим заполнения картинки в Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Устанавливает горизонтальный сдвиг текстуры в 20 пунктов
    pictureFillFormat.TileOffsetX = 20f;
}
```

### Смотрите Также

* класс [PictureFillFormat](../../picturefillformat)
* пространство имён [Aspose.Slides](../../picturefillformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->