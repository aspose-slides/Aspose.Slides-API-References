---
title: Handout
second_title: Aspose.Sildes для .NET API Reference
description: Указывает, сколько слайдов и в каком порядке будет размещено на странице HandoutTypeaspose.slides/handouttype.
type: docs
weight: 20
url: /ru/aspose.slides.export/handoutlayoutingoptions/handout/
---

## HandoutLayoutingOptions.Handout свойство

Указывает, сколько слайдов и в каком порядке будет размещено на странице [`HandoutType`](../../handouttype).

```csharp
public HandoutType Handout { get; set; }
```

### Примечания

Значение по умолчанию - **HandoutType.Handouts6Horizontal**.

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    RenderingOptions options = new RenderingOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Slides[0].GetThumbnail(options, new Size(1920, 1080)).Save("pres-handout.png");
}
```

### См. также

* enum [HandoutType](../../handouttype)
* class [HandoutLayoutingOptions](../../handoutlayoutingoptions)
* namespace [Aspose.Slides.Export](../../handoutlayoutingoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
