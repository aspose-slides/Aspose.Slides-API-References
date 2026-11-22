---
title: compress_presentation method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Minskar storleken på en presentation genom att tillämpa alla tillgängliga komprimeringssteg:
            
* Tar bort oanvända masterbilder **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Tar bort oanvända layoutbilder **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Behåller endast de glyfer som faktiskt används i inbäddade typsnitt **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Minskar bildens upplösning till 150 DPI och tar bort beskurna områden i bilder **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Presentation som ska komprimeras. |

### Anmärkningar

För att anpassa komprimeringen, till exempel för att använda en annan bildupplösning eller för att hoppa över ett steg, anropa metoderna som listas ovan individuellt istället för den här. Beskurna bildområden tas bort permanent och kan inte återställas i PowerPoint.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` är `None`. |



### Se också
* klass [`Compress`](/slides/python-net/sv/aspose.slides.lowcode/compress)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/sv/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)