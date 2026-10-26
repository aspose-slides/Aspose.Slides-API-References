---
title: IMasterSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/imasterslide/
---
## IMasterSlide klass

Representerar en master-bild i en presentation.

IMasterSlide-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/imasterslide/header_footer_manager/) | Returnerar HeaderFooter-hanteraren för master-bilden.<br/>            Skrivskyddad [`IMasterSlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/sv/aspose.slides/imasterslide/title_style/) | Returnerar stilen för en titeltext.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/sv/aspose.slides/imasterslide/body_style/) | Returnerar stilen för en brödtext.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/sv/aspose.slides/imasterslide/other_style/) | Returnerar stilen för en annan text.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/sv/aspose.slides/imasterslide/layout_slides/) | Returnerar samlingen av underordnade layout-bilder för denna master-bild.<br/>            Skrivskyddad [`IMasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/sv/aspose.slides/imasterslide/preserve/) | Bestämmer om den motsvarande master-bilden tas bort när alla <br/>            bilderna som följer den master-bilden har tagits bort.<br/>            Observera: Aspose.Slides kommer aldrig att ta bort någon oanvänd master på egen hand, <br/>            för att faktiskt ta bort oanvända master-bilder anropa **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Läs/skriv **bool**. |
| [`has_depending_slides`](/slides/python-net/sv/aspose.slides/imasterslide/has_depending_slides/) | Returnerar true om det finns minst en bild som beror på denna master-bild.<br/>            Skrivskyddad **bool**. |
| [`drawing_guides`](/slides/python-net/sv/aspose.slides/imasterslide/drawing_guides/) | Returnerar en samling ritguider för master-bilden.<br/>            Skrivskyddad [`IDrawingGuidesCollection`](/slides/python-net/sv/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/sv/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/sv/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/sv/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/sv/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/sv/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/sv/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/sv/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/imasterslide/theme_manager/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/sv/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Skapar en ny master-bild baserad på den aktuella, applicerar ett externt tema på den <br/>            och tillämpar den skapade master-bilden på alla beroende bilder. |
| [`get_depending_slides(self)`](/slides/python-net/sv/aspose.slides/imasterslide/get_depending_slides/#) | Returnerar en array med alla bilder som beror på denna master-bild. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/imasterslide/create_theme_effective/#) |  |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)