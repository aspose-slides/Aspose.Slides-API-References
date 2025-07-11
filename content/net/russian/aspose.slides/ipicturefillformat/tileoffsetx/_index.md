---
title: TileOffsetX
second_title: Aspose.Sildes для .NET API Справочник
description: Возвращает или задает горизонтальный сдвиг текстуры от начала формы в пунктах. Положительное значение смещает текстуру вправо, в то время как отрицательное значение смещает ее влево. Чтение/запись Single.
type: docs
weight: 150
url: /ru/aspose.slides/ipicturefillformat/tileoffsetx/
---

## IPictureFillFormat.TileOffsetX свойство

Возвращает или задает горизонтальный сдвиг текстуры от начала формы в пунктах. Положительное значение смещает текстуру вправо, в то время как отрицательное значение смещает ее влево. Чтение/запись Single.

```csharp
public float TileOffsetX { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Получает формат заполнения изображения формы
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Устанавливает режим заполнения изображения в Плитка
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Устанавливает горизонтальный сдвиг текстуры на 20 пунктов
    pictureFillFormat.TileOffsetX = 20f;
}
```

### Смотрите Также

* интерфейс [IPictureFillFormat](../../ipicturefillformat)
* пространство имен [Aspose.Slides](../../ipicturefillformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->