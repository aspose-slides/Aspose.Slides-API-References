---
title: IMasterSlide class
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/imasterslide/
---
## IMasterSlide klasa

Represents a master slide in a presentation.

The IMasterSlide type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/imasterslide/header_footer_manager/) | Zwraca menedżer HeaderFooter slajdu głównego.<br/>            Tylko do odczytu [`IMasterSlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/pl/aspose.slides/imasterslide/title_style/) | Zwraca styl tekstu tytułowego.<br/>            Tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/pl/aspose.slides/imasterslide/body_style/) | Zwraca styl tekstu podstawowego.<br/>            Tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/pl/aspose.slides/imasterslide/other_style/) | Zwraca styl innego tekstu.<br/>            Tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/pl/aspose.slides/imasterslide/layout_slides/) | Zwraca kolekcję podrzędnych slajdów układu dla tego slajdu głównego.<br/>            Tylko do odczytu [`IMasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/pl/aspose.slides/imasterslide/preserve/) | Określa, czy odpowiedni master jest usuwany, gdy wszystkie <br/>            slajdy podążające za tym masterem zostaną usunięte.<br/>            Uwaga: Aspose.Slides nigdy nie usunie nieużywanego mastera samodzielnie, <br/>            aby faktycznie usunąć nieużywane mastery, wywołaj **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Odczyt/zapis **bool**. |
| [`has_depending_slides`](/slides/python-net/pl/aspose.slides/imasterslide/has_depending_slides/) | Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu głównego.<br/>            Tylko do odczytu **bool**. |
| [`drawing_guides`](/slides/python-net/pl/aspose.slides/imasterslide/drawing_guides/) | Zwraca kolekcję prowadnic rysunkowych dla slajdu głównego.<br/>            Tylko do odczytu [`IDrawingGuidesCollection`](/slides/python-net/pl/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/pl/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/pl/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/pl/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/pl/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/pl/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/pl/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/pl/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/imasterslide/theme_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/pl/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Tworzy nowy slajd główny na podstawie bieżącego, stosując zewnętrzny motyw <br/>            i aplikuje utworzony slajd główny do wszystkich zależnych slajdów. |
| [`get_depending_slides(self)`](/slides/python-net/pl/aspose.slides/imasterslide/get_depending_slides/#) | Zwraca tablicę ze wszystkimi slajdami zależnymi od tego slajdu głównego. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/imasterslide/create_theme_effective/#) |  |


### See Also
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)