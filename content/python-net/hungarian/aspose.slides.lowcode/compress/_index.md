---
title: Compress class
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás segítségével
description: 
type: docs
url: /hu/aspose.slides.lowcode/compress/
---
## Compress osztály

A [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) tömörítésére szolgáló metóduscsoportot képvisel.

A Compress típus a következő tagokat teszi közzé:

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/hu/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Csökkenti a bemutató méretét az összes elérhető tömörítési lépés alkalmazásával:<br/>            <br/>* Eltávolítja a nem használt mesterdiapozitívákat **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Eltávolítja a nem használt elrendezési diákot **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Csak a beágyazott betűkészletekben ténylegesen használt jeleket tartja meg **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* 150 DPI-re csökkenti a képek felbontását és törli a képek levágott részeit **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/hu/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | A [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) tömörítését végzi a nem használt mesterdiapozitívák eltávolításával. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/hu/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | A [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) tömörítését végzi a nem használt elrendezési diákok eltávolításával. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/hu/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | A [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) tömörítését végzi a beágyazott betűkészletekből a nem használt karakterek eltávolításával. |
| [`compress_images(presentation, resolution)`](/slides/python-net/hu/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Csökkenti a bemutató képeinek felbontását és törli a levágott részeket,<br/>            hasonlóan a PowerPoint "Compress Pictures" funkciójához, amely minden képre alkalmazva van.<br/>            A diákon, elrendezési diákon és mesterdiákon lévő képek feldolgozásra kerülnek, beleértve a csoportos alakzatokban lévő képeket<br/>            és az alakzatok képpel való kitöltését. |


### Lásd még
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/hu/aspose.slides.lowcode)
* könyvtár [`Aspose.Slides`](/slides/python-net)