---
title: Slide class
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/slide/
---
## Slide klasa

Represents a slide in a presentation.

**Dziedziczenie:**[`Slide`](/slides/python-net/pl/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)

Typ Slide udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/slide/shapes/) | Zwraca kształty slajdu.<br/>            Tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/slide/controls/) | Zwraca kolekcję kontrolek ActiveX na slajdzie.<br/>            Tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/slide/name/) | Zwraca lub ustawia nazwę slajdu.<br/>            Odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/slide/slide_id/) | Zwraca identyfikator slajdu.<br/>            Tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/slide/custom_data/) | Zwraca własne dane slajdu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/slide/timeline/) | Zwraca obiekt osi czasu animacji.<br/>            Tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/slide/slide_show_transition/) | Zwraca obiekt Transition, który zawiera informacje o<br/>            tym, jak określony slajd przechodzi w trakcie pokazu slajdów.<br/>            Tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/slide/background/) | Zwraca tło slajdu.<br/>            Tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/slide/hyperlink_queries/) | Zapewnia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/slide/show_master_shapes/) | Określa, czy kształty na slajdzie master mają być wyświetlane na slajdach, czy nie.<br/>            Odczyt/zapis **bool**. |
| [`presentation`](/slides/python-net/pl/aspose.slides/slide/presentation/) | Zwraca interfejs IPresentation.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/slide/header_footer_manager/) | Zwraca menedżera HeaderFooter slajdu.<br/>            Tylko do odczytu [`ISlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/slide/theme_manager/) | Zwraca menedżera nadpisującego tematu.<br/>            Tylko do odczytu [`IOverrideThemeManager`](/slides/python-net/pl/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/pl/aspose.slides/slide/slide_number/) | Zwraca numer slajdu.<br/>            Indeks slajdu w kolekcji [`Presentation.slides`](/slides/python-net/pl/aspose.slides/presentation/slides) jest zawsze równy SlideNumber - Presentation.FirstSlideNumber.<br/>            Odczyt/zapis **int**. |
| [`hidden`](/slides/python-net/pl/aspose.slides/slide/hidden/) | Określa, czy określony slajd jest ukryty podczas pokazu slajdów.<br/>            Odczyt/zapis **bool**. |
| [`layout_slide`](/slides/python-net/pl/aspose.slides/slide/layout_slide/) | Zwraca lub ustawia slajd układu dla bieżącego slajdu.<br/>            Odczyt/zapis [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/pl/aspose.slides/slide/notes_slide_manager/) | Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go.<br/>            Tylko do odczytu [`INotesSlideManager`](/slides/python-net/pl/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/pl/aspose.slides/slide/slide/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/slide/join_portions_with_same_formatting/#) | Łączy ciągi znaków o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pl/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Łączy ciągi znaków o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/slide/get_image/#float-float) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/slide/get_image/#) | Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru). |
| [`get_image(self, image_size)`](/slides/python-net/pl/aspose.slides/slide/get_image/#asposeslidessize) | Zwraca obiekt Thumbnail Image o określonym rozmiarze. |
| [`get_image(self, options)`](/slides/python-net/pl/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Zwraca obiekt miniatury obrazu TIFF z określonymi parametrami. |
| [`get_image(self, options)`](/slides/python-net/pl/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Zwraca obiekt Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [`get_image(self, options, image_size)`](/slides/python-net/pl/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Zwraca obiekt Thumbnail Image o określonym rozmiarze. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/slide/write_as_svg/#iorawiobase) | Zapisuje zawartość slajdu jako plik SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Zapisuje zawartość slajdu jako plik SVG. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/slide/equals/#ibaseslide) | Określa, czy dwie instancje IBaseSlide są równe.<br/>            Wartość zwracana jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itd. są identyczne. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz treści dynamicznej, np. bieżącej wartości daty w znaczniku daty. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/slide/create_theme_effective/#) | Zwraca efektywny temat dla tego slajdu. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/slide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |
| [`write_as_emf(self, stream)`](/slides/python-net/pl/aspose.slides/slide/write_as_emf/#iorawiobase) | Zapisuje zawartość slajdu jako plik EMF. |
| [`remove(self)`](/slides/python-net/pl/aspose.slides/slide/remove/#) | Usuwa slajd z prezentacji. |
| [`reset(self)`](/slides/python-net/pl/aspose.slides/slide/reset/#) | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/pl/aspose.slides/slide/get_slide_comments/#icommentauthor) | Zwraca wszystkie komentarze slajdu dodane przez określonego autora. |

### Zobacz także
* klasa [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)
* klasa [`Slide`](/slides/python-net/pl/aspose.slides/slide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)