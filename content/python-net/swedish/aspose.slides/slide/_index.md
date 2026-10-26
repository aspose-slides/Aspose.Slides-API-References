---
title: Slide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/slide/
---
## Slide klass

Representerar en slide i en presentation.

**Inheritance:**[`Slide`](/slides/python-net/sv/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)

Slide-typen exponeras följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/slide/shapes/) | Returnerar formerna på en slide.<br/>            Endast läsning [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/slide/controls/) | Returnerar samlingen av ActiveX-kontroller på en slide.<br/>            Endast läsning [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/slide/name/) | Returnerar eller sätter namnet på en slide.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/slide/slide_id/) | Returnerar ID för en slide.<br/>            Endast läsning **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/slide/custom_data/) | Returnerar slidens anpassade data.<br/>            Endast läsning [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/slide/timeline/) | Returnerar animations-tidslinjeobjekt.<br/>            Endast läsning [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/slide/slide_show_transition/) | Returnerar Transition-objektet som innehåller information om<br/>            hur den valda sliden avancerar under en bildspel.<br/>            Endast läsning [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/slide/background/) | Returnerar slidens bakgrund.<br/>            Endast läsning [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/slide/hyperlink_queries/) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar.<br/>            Endast läsning [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/slide/show_master_shapes/) | Anger om former på mastern sliden ska visas på slides eller inte.<br/>            Läs/skriv **bool**. |
| [`presentation`](/slides/python-net/sv/aspose.slides/slide/presentation/) | Returnerar IPresentation-gränssnitt.<br/>            Endast läsning [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/slide/header_footer_manager/) | Returnerar HeaderFooter-hanterare för sliden.<br/>            Endast läsning [`ISlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/slide/theme_manager/) | Returnerar den överskrivande temahanteraren.<br/>            Endast läsning [`IOverrideThemeManager`](/slides/python-net/sv/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/sv/aspose.slides/slide/slide_number/) | Returnerar ett nummer för sliden.<br/>            Index för sliden i [`Presentation.slides`](/slides/python-net/sv/aspose.slides/presentation/slides)-samlingen är alltid lika med SlideNumber - Presentation.FirstSlideNumber.<br/>            Läs/skriv **int**. |
| [`hidden`](/slides/python-net/sv/aspose.slides/slide/hidden/) | Bestämmer om den angivna sliden är gömd under ett bildspel.<br/>            Läs/skriv **bool**. |
| [`layout_slide`](/slides/python-net/sv/aspose.slides/slide/layout_slide/) | Returnerar eller sätter layout-sliden för den aktuella sliden.<br/>            Läs/skriv [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/sv/aspose.slides/slide/notes_slide_manager/) | Tillåter åtkomst till notes-slide, lägga till och ta bort den.<br/>            Endast läsning [`INotesSlideManager`](/slides/python-net/sv/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/sv/aspose.slides/slide/slide/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/slide/join_portions_with_same_formatting/#) | Slår ihop körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/sv/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Slår ihop körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/slide/get_image/#float-float) | Returnerar ett Thumbnail Image-objekt med anpassad skalning. |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/slide/get_image/#) | Returnerar ett Thumbnail Image-objekt (20 % av verklig storlek). |
| [`get_image(self, image_size)`](/slides/python-net/sv/aspose.slides/slide/get_image/#asposeslidessize) | Returnerar ett Thumbnail Image-objekt med angiven storlek. |
| [`get_image(self, options)`](/slides/python-net/sv/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Returnerar ett Thumbnail tiff-bildobjekt med angivna parametrar. |
| [`get_image(self, options)`](/slides/python-net/sv/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Returnerar ett Thumbnail Image-objekt. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Returnerar ett Thumbnail Image-objekt med anpassad skalning. |
| [`get_image(self, options, image_size)`](/slides/python-net/sv/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Returnerar ett Thumbnail Image-objekt med angiven storlek. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/slide/write_as_svg/#iorawiobase) | Sparar slidens innehåll som en SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar slidens innehåll som en SVG-fil. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/slide/equals/#ibaseslide) | Bestämmer om de två IBaseSlide-instanserna är lika.<br/>            Returvärdet beräknas baserat på slidens struktur och statiska innehåll.<br/>            Två slides är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/slide/create_theme_effective/#) | Returnerar ett effektivt tema för denna slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/slide/find_shape_by_alt_text/#str) | Hittar första förekomsten av en form med angiven alternativ text. |
| [`write_as_emf(self, stream)`](/slides/python-net/sv/aspose.slides/slide/write_as_emf/#iorawiobase) | Sparar slidens innehåll som en EMF-fil. |
| [`remove(self)`](/slides/python-net/sv/aspose.slides/slide/remove/#) | Tar bort sliden från presentationen. |
| [`reset(self)`](/slides/python-net/sv/aspose.slides/slide/reset/#) | Återställer position, storlek och formatering för varje form som har en prototype på LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/sv/aspose.slides/slide/get_slide_comments/#icommentauthor) | Returnerar alla slide-kommentarer som lagts till av en specifik författare. |

### Se också
* klass [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)
* klass [`Slide`](/slides/python-net/sv/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)