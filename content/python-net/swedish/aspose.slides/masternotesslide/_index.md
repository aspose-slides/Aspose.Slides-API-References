---
title: MasterNotesSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masternotesslide/
---
## MasterNotesSlide klass

Representerar masterbild för anteckningar.

**Arv:**[`MasterNotesSlide`](/slides/python-net/sv/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)

Typen MasterNotesSlide exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/masternotesslide/shapes/) | Returnerar formerna på en bild.<br/>            Skrivskyddad [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/masternotesslide/controls/) | Returnerar samlingen av ActiveX-kontroller på en bild.<br/>            Skrivskyddad [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/masternotesslide/name/) | Returnerar eller anger namn på en bild.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/masternotesslide/slide_id/) | Returnerar ID för en bild.<br/>            Skrivskyddad **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/masternotesslide/custom_data/) | Returnerar bildens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/masternotesslide/timeline/) | Returnerar animations-tidslinje-objekt.<br/>            Skrivskyddad [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/masternotesslide/slide_show_transition/) | Returnerar Transition-objektet som innehåller information om<br/>            hur den angivna bilden avancerar under ett bildspel.<br/>            Skrivskyddad [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/masternotesslide/background/) | Returnerar bildens bakgrund.<br/>            Skrivskyddad [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/masternotesslide/hyperlink_queries/) | Ger enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/masternotesslide/show_master_shapes/) | Anger om former på masterbilden ska visas på bilder eller inte.<br/>            För masterbilden själv returnerar denna egenskap alltid `false`.<br/>            Läs/skriv **bool**. |
| [`presentation`](/slides/python-net/sv/aspose.slides/masternotesslide/presentation/) | Returnerar IPresentation-gränssnittet.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/masternotesslide/header_footer_manager/) | Returnerar HeaderFooter-hanteraren för masteranteckningsbilden.<br/>            Skrivskyddad [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/masternotesslide/theme_manager/) | Returnerar temahanteraren.<br/>            Skrivskyddad [`IMasterThemeManager`](/slides/python-net/sv/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/sv/aspose.slides/masternotesslide/notes_style/) | Returnerar stilen för en anteckningstext.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/sv/aspose.slides/masternotesslide/drawing_guides/) | Returnerar en samling ritningsguider för masteranteckningsbilden.<br/>            Skrivskyddad [`IDrawingGuidesCollection`](/slides/python-net/sv/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/sv/aspose.slides/masternotesslide/slide/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/sv/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/masternotesslide/equals/#ibaseslide) | Bestämmer om de två IBaseSlide-instanserna är lika.<br/>            Återvändande värde beräknas baserat på bildens struktur och statiska innehåll.<br/>            Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i datumplatshållare. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/masternotesslide/create_theme_effective/#) | Returnerar ett effektivt tema för denna bild. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Hittar första förekomsten av en form med den angivna alternativa texten. |

### Se även
* klass [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)
* klass [`MasterNotesSlide`](/slides/python-net/sv/aspose.slides/masternotesslide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)