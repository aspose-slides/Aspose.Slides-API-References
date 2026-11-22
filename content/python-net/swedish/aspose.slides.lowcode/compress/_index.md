---
title: Compress class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.lowcode/compress/
---
## Compress klass

Representerar en grupp metoder avsedda att komprimera [`Presentation`](/slides/python-net/sv/aspose.slides/presentation).

Compress-typen exponerar följande medlemmar:

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/sv/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Minskar storleken på en presentation genom att tillämpa alla tillgängliga komprimeringssteg:<br/>            <br/>* Tar bort oanvända masterbilder **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Tar bort oanvända layoutbilder **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Behåller endast de glyfer som faktiskt används i inbäddade typsnitt **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Minskar bildupplösning till 150 DPI och tar bort beskurna områden av bilder **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/sv/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Komprimerar [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) genom att ta bort oanvända masterbilder. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/sv/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Komprimerar [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) genom att ta bort oanvända layoutbilder. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/sv/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Komprimerar [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) genom att ta bort oanvända tecken från inbäddade typsnitt. |
| [`compress_images(presentation, resolution)`](/slides/python-net/sv/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Reducerar upplösningen på bilder i presentationen och tar bort deras beskurna områden,<br/>            liknande PowerPoints “Compress Pictures” som tillämpas på alla bilder.<br/>            Bilder på bilder, layoutbilder och masterbilder bearbetas, inklusive bilder i gruppformer<br/>            och bildfyllningar i former. |


### Se även
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/sv/aspose.slides.lowcode)
* bibliotek [`Aspose.Slides`](/slides/python-net)