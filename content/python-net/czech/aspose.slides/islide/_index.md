---
title: ISlide class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/islide/
---
## třída ISlide

Reprezentuje snímek v prezentaci.

Typ ISlide obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/islide/header_footer_manager/) | Vrací správce HeaderFooter snímku.<br/>            Pouze pro čtení [`ISlideHeaderFooterManager`](/slides/python-net/cs/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/cs/aspose.slides/islide/slide_number/) | Vrací číslo snímku.<br/>            Index snímku v kolekci [`IPresentation.slides`](/slides/python-net/cs/aspose.slides/ipresentation/slides) je vždy roven SlideNumber - 1.<br/>            Čtení / zápis **int**. |
| [`hidden`](/slides/python-net/cs/aspose.slides/islide/hidden/) | Určuje, zda je určený snímek během promítání skrytý.<br/>            Čtení / zápis **bool**. |
| [`layout_slide`](/slides/python-net/cs/aspose.slides/islide/layout_slide/) | Vrací nebo nastavuje rozložení snímku pro aktuální snímek.<br/>            Čtení / zápis [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/cs/aspose.slides/islide/notes_slide_manager/) | Umožňuje přístup k poznámkovému snímku, přidávat jej a odebírat.<br/>            Pouze pro čtení [`INotesSlideManager`](/slides/python-net/cs/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/cs/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/cs/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/cs/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/cs/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/cs/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/cs/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/cs/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/cs/aspose.slides/islide/theme_manager/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/islide/get_image/#float-float) | Vrací objekt obrázku s vlastním měřítkem. |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/islide/get_image/#) | Vrací miniaturu obrázku (20 % skutečné velikosti). |
| [`get_image(self, image_size)`](/slides/python-net/cs/aspose.slides/islide/get_image/#asposepydrawingsize) | Vrací objekt obrázku se zadanou velikostí. |
| [`get_image(self, options)`](/slides/python-net/cs/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Vrací miniaturu bitmapy TIFF s určenými parametry. |
| [`get_image(self, options)`](/slides/python-net/cs/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Vrací miniaturu bitmapy. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Vrací miniaturu bitmapy s vlastním měřítkem. |
| [`get_image(self, options, image_size)`](/slides/python-net/cs/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Vrací miniaturu bitmapy se zadanou velikostí. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/islide/write_as_svg/#iorawiobase) | Uloží obsah snímku jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah snímku jako soubor SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/cs/aspose.slides/islide/get_slide_comments/#icommentauthor) | Vrací všechny komentáře ke snímku přidané konkrétním autorem. |
| [`write_as_emf(self, stream)`](/slides/python-net/cs/aspose.slides/islide/write_as_emf/#iorawiobase) | Uloží obsah snímku jako soubor EMF. |
| [`remove(self)`](/slides/python-net/cs/aspose.slides/islide/remove/#) | Odstraní snímek z prezentace. |
| [`reset(self)`](/slides/python-net/cs/aspose.slides/islide/reset/#) | Resetuje pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/islide/create_theme_effective/#) |  |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)