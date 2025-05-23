---
title: SlidesLayoutOptions
second_title: Aspose.Sildes for .NET API Reference
description: Gets or sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 40
url: /aspose.slides.export/renderingoptions/slideslayoutoptions/
---

## RenderingOptions.SlidesLayoutOptions property

Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](../../islideslayoutoptions).

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    RenderingOptions options = new RenderingOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal,
            PrintSlideNumbers = false
        }
    };
    
    Bitmap[] handoutSlides = pres.GetThumbnails(options);
    for (var index = 0; index < handoutSlides.Length; index++)
    {
        var handoutSllide = handoutSlides[index];
        handoutSllide.Save($"handout-{index}.png");
    }
}
```

### See Also

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* class [RenderingOptions](../../renderingoptions)
* namespace [Aspose.Slides.Export](../../renderingoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
