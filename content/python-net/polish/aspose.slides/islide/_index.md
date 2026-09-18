---
title: ISlide class
second_title: Odwołanie API Aspose.Slides dla Pythona przy użyciu .NET
description: 
type: docs
url: /pl/aspose.slides/islide/
---
## ISlide klasa

Reprezentuje slajd w prezentacji.

Typ ISlide udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/islide/header_footer_manager/) | Zwraca menedżera HeaderFooter slajdu.<br/>            Tylko do odczytu [`ISlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/pl/aspose.slides/islide/slide_number/) | Zwraca numer slajdu.<br/>            Indeks slajdu w kolekcji [`IPresentation.slides`](/slides/python-net/pl/aspose.slides/ipresentation/slides) jest zawsze równy SlideNumber - 1.<br/>            Odczyt/zapis **int**. |
| [`hidden`](/slides/python-net/pl/aspose.slides/islide/hidden/) | Określa, czy podany slajd jest ukryty podczas pokazu slajdów.<br/>            Odczyt/zapis **bool**. |
| [`layout_slide`](/slides/python-net/pl/aspose.slides/islide/layout_slide/) | Zwraca lub ustawia slajd układu dla bieżącego slajdu.<br/>            Odczyt/zapis [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/pl/aspose.slides/islide/notes_slide_manager/) | Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go.<br/>            Tylko do odczytu [`INotesSlideManager`](/slides/python-net/pl/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/pl/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/pl/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/pl/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/pl/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/pl/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/pl/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/pl/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/islide/theme_manager/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/islide/get_image/#float-float) | Zwraca obiekt obrazu ze skalowaniem niestandardowym. |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/islide/get_image/#) | Zwraca obiekt miniatury obrazu (20% rzeczywistego rozmiaru). |
| [`get_image(self, image_size)`](/slides/python-net/pl/aspose.slides/islide/get_image/#asposepydrawingsize) | Zwraca obiekt obrazu o określonym rozmiarze. |
| [`get_image(self, options)`](/slides/python-net/pl/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Zwraca miniaturę bitmapy tiff z określonymi parametrami. |
| [`get_image(self, options)`](/slides/python-net/pl/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Zwraca miniaturę obiektu Bitmap. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Zwraca miniaturę obiektu Bitmap ze skalowaniem niestandardowym. |
| [`get_image(self, options, image_size)`](/slides/python-net/pl/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Zwraca miniaturę obiektu Bitmap o określonym rozmiarze. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/islide/write_as_svg/#iorawiobase) | Zapisuje zawartość slajdu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość slajdu jako plik SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/pl/aspose.slides/islide/get_slide_comments/#icommentauthor) | Zwraca wszystkie komentarze slajdu dodane przez określonego autora. |
| [`write_as_emf(self, stream)`](/slides/python-net/pl/aspose.slides/islide/write_as_emf/#iorawiobase) | Zapisuje zawartość slajdu jako plik EMF. |
| [`remove(self)`](/slides/python-net/pl/aspose.slides/islide/remove/#) | Usuwa slajd z prezentacji. |
| [`reset(self)`](/slides/python-net/pl/aspose.slides/islide/reset/#) | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/islide/create_theme_effective/#) |  |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)