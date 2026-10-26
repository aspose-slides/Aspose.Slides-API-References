---
title: LayoutSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/layoutslide/
---
## LayoutSlide klass

Representerar en layout-bild.

**Inheritance:**[`LayoutSlide`](/slides/python-net/sv/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)

LayoutSlide-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/layoutslide/shapes/) | Returnerar formerna på en bild.<br/>            Skrivskyddad [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/layoutslide/controls/) | Returnerar samlingen av ActiveX-kontroller på en bild.<br/>            Skrivskyddad [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/layoutslide/name/) | Returnerar eller anger namn på en bild.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/layoutslide/slide_id/) | Returnerar bildens ID.<br/>            Skrivskyddad **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/layoutslide/custom_data/) | Returnerar bildens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/layoutslide/timeline/) | Returnerar animations-tidslinjeobjekt.<br/>            Skrivskyddad [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/layoutslide/slide_show_transition/) | Returnerar Transition-objektet som innehåller information om<br/>            hur den angivna bilden avancerar under ett bildspel.<br/>            Skrivskyddad [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/layoutslide/background/) | Returnerar bildens bakgrund.<br/>            Skrivskyddad [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/layoutslide/hyperlink_queries/) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/layoutslide/show_master_shapes/) | Anger om former på mastern ska visas på bilder eller inte.<br/>            Läs/skriv **bool**. |
| [`presentation`](/slides/python-net/sv/aspose.slides/layoutslide/presentation/) | Returnerar IPresentation-gränssnitt.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/layoutslide/header_footer_manager/) | Returnerar HeaderFooter-hanteraren för layout-bilden.<br/>            Skrivskyddad [`ILayoutSlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/sv/aspose.slides/layoutslide/placeholder_manager/) | Returnerar platshållar-hanteraren för layout-bilden.<br/>            Skrivskyddad [`ILayoutPlaceholderManager`](/slides/python-net/sv/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/sv/aspose.slides/layoutslide/master_slide/) | Returnerar eller anger mastern för en layout.<br/>            Läs/skriv [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/layoutslide/theme_manager/) | Returnerar den överskrivande temahanteraren.<br/>            Skrivskyddad [`IOverrideThemeManager`](/slides/python-net/sv/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/sv/aspose.slides/layoutslide/layout_type/) | Returnerar layout-typ för denna layout-bild.<br/>            Skrivskyddad [`SlideLayoutType`](/slides/python-net/sv/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/sv/aspose.slides/layoutslide/has_depending_slides/) | Returnerar true om det finns minst en bild som är beroende av denna layout-bild.<br/>            Skrivskyddad **bool**. |
| [`drawing_guides`](/slides/python-net/sv/aspose.slides/layoutslide/drawing_guides/) | Returnerar en samling ritningsguider för layout-bilden.<br/>            Skrivskyddad [`IDrawingGuidesCollection`](/slides/python-net/sv/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/sv/aspose.slides/layoutslide/slide/) |  |

## Metoder

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Slår samman körningar med samma formatering i alla stycken i alla godkända former. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/sv/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Slår samman körningar med samma formatering i alla stycken i alla godkända former. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/layoutslide/equals/#ibaseslide) | Avgör om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på bildens struktur och statiska innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i datum-platshållare. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/layoutslide/create_theme_effective/#) | Returnerar ett effektivt tema för denna bild. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Hittar första förekomsten av en form med den angivna alternativa texten. |
| [`remove(self)`](/slides/python-net/sv/aspose.slides/layoutslide/remove/#) | Tar bort layout från presentationen. |
| [`get_depending_slides(self)`](/slides/python-net/sv/aspose.slides/layoutslide/get_depending_slides/#) | Returnerar en array med alla bilder som är beroende av denna layout-bild. |

### Se också
* klass [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)
* klass [`LayoutSlide`](/slides/python-net/sv/aspose.slides/layoutslide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)