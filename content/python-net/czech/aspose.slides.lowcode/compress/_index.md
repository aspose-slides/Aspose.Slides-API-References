---
title: Compress class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.lowcode/compress/
---
## třída Compress

Představuje skupinu metod určených k kompresi [`Presentation`](/slides/python-net/cs/aspose.slides/presentation).

Typ Compress poskytuje následující členy:

## Metody

| Metoda | Popis |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/cs/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Sníží velikost prezentace použitím všech dostupných kroků komprese:<br/>            <br/>* Odstraňuje nepoužité hlavní snímky **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Odstraňuje nepoužité rozložení snímků **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Zachovává pouze glyfy skutečně použité v vložených fontech **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Sníží rozlišení obrázků na 150 DPI a smaže oříznuté oblasti obrázků **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/cs/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Provádí kompresi [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) odstraněním nepoužitých hlavních snímků. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/cs/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Provádí kompresi [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) odstraněním nepoužitých rozložení snímků. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/cs/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Provádí kompresi [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) odstraněním nepoužitých znaků z vložených fontů. |
| [`compress_images(presentation, resolution)`](/slides/python-net/cs/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Sníží rozlišení obrázků v prezentaci a smaže jejich oříznuté části,<br/>            podobně jako funkce PowerPointu „Compress Pictures“ použita na všechny obrázky.<br/>            Obrázky na snímcích, rozložení snímků a hlavních snímcích jsou zpracovány, včetně obrázků uvnitř skupinových tvarů<br/>            a vyplnění obrázků tvarů. |

### Viz také
* třída [`Presentation`](/slides/python-net/cs/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/cs/aspose.slides.lowcode)
* knihovna [`Aspose.Slides`](/slides/python-net)