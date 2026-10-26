---
title: MasterHandoutSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide klass

Representerar masterbild för handouts.

**Arv:**[`MasterHandoutSlide`](/slides/python-net/sv/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)

MasterHandoutSlide-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/masterhandoutslide/shapes/) | Returnerar formerna på en bild.<br/>            Skrivskyddad [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/masterhandoutslide/controls/) | Returnerar samlingen av ActiveX-kontroller på en bild.<br/>            Skrivskyddad [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/masterhandoutslide/name/) | Returnerar eller anger namnet på en bild.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/masterhandoutslide/slide_id/) | Returnerar ID-t för en bild.<br/>            Skrivskyddad **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/masterhandoutslide/custom_data/) | Returnerar bildens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/masterhandoutslide/timeline/) | Returnerar animations-tidslinjeobjektet.<br/>            Skrivskyddad [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/masterhandoutslide/slide_show_transition/) | Returnerar Transition-objektet som innehåller information om<br/>            hur den angivna bilden avancerar under en bildspel.<br/>            Skrivskyddad [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/masterhandoutslide/background/) | Returnerar bildens bakgrund.<br/>            Skrivskyddad [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/masterhandoutslide/hyperlink_queries/) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/masterhandoutslide/show_master_shapes/) | Anger om former på master-bilden ska visas på bilder eller inte.<br/>            För själva master-bilden returnerar denna egenskap alltid `false`.<br/>            Läs/skriv **bool**. |
| [`presentation`](/slides/python-net/sv/aspose.slides/masterhandoutslide/presentation/) | Returnerar IPresentation-gränssnittet.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/masterhandoutslide/header_footer_manager/) | Returnerar HeaderFooter-hanteraren för master-handout-bilden.<br/>            Skrivskyddad [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/masterhandoutslide/theme_manager/) | Returnerar temahanteraren.<br/>            Skrivskyddad [`IMasterThemeManager`](/slides/python-net/sv/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/sv/aspose.slides/masterhandoutslide/drawing_guides/) | Returnerar en samling av ritningsguider för master-handout-bilden.<br/>            Skrivskyddad [`IDrawingGuidesCollection`](/slides/python-net/sv/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/sv/aspose.slides/masterhandoutslide/slide/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/sv/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Bestämmer om de två IBaseSlide-instanserna är lika.<br/>            Returnerat värde beräknas baserat på bildens struktur och statiska innehåll.<br/>            Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifieringsvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i datum-platshållare. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/masterhandoutslide/create_theme_effective/#) | Returnerar ett effektivt tema för denna bild. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Hittar den första förekomsten av en form med den angivna alternativa texten. |

### Se också
* klass [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)
* klass [`MasterHandoutSlide`](/slides/python-net/sv/aspose.slides/masterhandoutslide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)