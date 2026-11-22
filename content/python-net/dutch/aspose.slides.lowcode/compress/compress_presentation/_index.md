---
title: compress_presentation method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Vermindert de grootte van een presentatie door alle beschikbare compressiestappen toe te passen:

* Verwijdert ongebruikte masterslides **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Verwijdert ongebruikte lay-outslides **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Behoudt alleen de daadwerkelijk gebruikte glyphs in ingesloten lettertypen **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Verlaagt de beeldresolutie naar 150 DPI en verwijdert bijgesneden delen van afbeeldingen **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De presentatie om te comprimeren. |

### Opmerkingen

Om compressie aan te passen, bijvoorbeeld om een andere beeldresolutie te gebruiken of om een stap over te slaan, roep de hierboven genoemde methoden individueel aan in plaats van deze. Bijgesneden delen van afbeeldingen worden permanent verwijderd en kunnen niet worden hersteld in PowerPoint.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |

### Zie ook
* klasse [`Compress`](/slides/python-net/nl/aspose.slides.lowcode/compress)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)