---
title: Compress class
second_title: Aspose.Slides dla Pythona przez .NET API
description: 
type: docs
url: /pl/aspose.slides.lowcode/compress/
---
## Klasa Compress

Reprezentuje grupę metod przeznaczonych do kompresji [`Presentation`](/slides/python-net/pl/aspose.slides/presentation).

Typ Compress udostępnia następujące elementy:

## Metody

| Metoda | Opis |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/pl/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Zmniejsza rozmiar prezentacji, stosując wszystkie dostępne kroki kompresji:<br/>            <br/>* Usuwa nieużywane slajdy master **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Usuwa nieużywane slajdy układu **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Zachowuje tylko glify faktycznie użyte w osadzonych czcionkach **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Zmniejsza rozdzielczość obrazów do 150 DPI i usuwa przycięte fragmenty obrazów **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/pl/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Wykonuje kompresję [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów master. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/pl/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Wykonuje kompresję [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów układu. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/pl/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Wykonuje kompresję [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) poprzez usunięcie nieużywanych znaków z osadzonych czcionek. |
| [`compress_images(presentation, resolution)`](/slides/python-net/pl/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Zmniejsza rozdzielczość obrazów w prezentacji i usuwa ich przycięte fragmenty,<br/>            podobnie jak funkcja „Compress Pictures” w PowerPoint zastosowana do wszystkich obrazów.<br/>            Obrazy na slajdach, slajdach układu i slajdach master są przetwarzane, w tym obrazy wewnątrz grup kształtów<br/>            oraz wypełnienia obrazami kształtów. |


### Zobacz również
* klasa [`Presentation`](/slides/python-net/pl/aspose.slides/presentation)
* moduł [`aspose.slides.lowcode`](/slides/python-net/pl/aspose.slides.lowcode)
* biblioteka [`Aspose.Slides`](/slides/python-net)