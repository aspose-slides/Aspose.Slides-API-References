---
title: Compress
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7170
url: /net/aspose.slides.lowcode/compress/
---
## Compress class

Represents a group of methods intended to compress [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Compress
```

## Methods

| Name | Description |
| --- | --- |
| static [RemoveUnusedLayoutSlides](../../aspose.slides.lowcode/compress/removeunusedlayoutslides)(Presentation) | Makes compression of the [`Presentation`](../../aspose.slides/presentation) by removing unused layout slides. |
| static [RemoveUnusedMasterSlides](../../aspose.slides.lowcode/compress/removeunusedmasterslides)(Presentation) | Makes compression of the [`Presentation`](../../aspose.slides/presentation) by removing unused master slides. |

### Examples

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedImages(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### See Also

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->