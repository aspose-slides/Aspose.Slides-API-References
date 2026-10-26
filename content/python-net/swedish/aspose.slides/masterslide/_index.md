---
title: MasterSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterslide/
---
## MasterSlide klass

Representerar en masterbild i en presentation.

**Arv:**[`MasterSlide`](/slides/python-net/sv/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)

MasterSlide-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/masterslide/shapes/) | Returnerar formerna på en bild.<br/>            Skrivskyddad [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/masterslide/controls/) | Returnerar samlingen av ActiveX-kontroller på en bild.<br/>            Skrivskyddad [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/masterslide/name/) | Returnerar eller anger namnet på en masterbild.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/masterslide/slide_id/) | Returnerar ID-t för en bild.<br/>            Skrivskyddad **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/masterslide/custom_data/) | Returnerar bildens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/masterslide/timeline/) | Returnerar animations-tidslinjeobjektet.<br/>            Skrivskyddad [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/masterslide/slide_show_transition/) | Returnerar Transition-objektet som innehåller information om<br/>            hur den angivna bilden avancerar under en bildspelsvisning.<br/>            Skrivskyddad [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/masterslide/background/) | Returnerar bildens bakgrund.<br/>            Skrivskyddad [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/masterslide/hyperlink_queries/) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/masterslide/show_master_shapes/) | Anger om former på masterbilden ska visas på bilder eller inte.<br/>            För själva masterbilden returnerar denna egenskap alltid `false`.<br/>            Läs/skriv **bool**. |
| [`presentation`](/slides/python-net/sv/aspose.slides/masterslide/presentation/) | Returnerar IPresentation-gränssnittet.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/masterslide/header_footer_manager/) | Returnerar HeaderFooter-hanteraren för masterbilden.<br/>            Skrivskyddad [`IMasterSlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/sv/aspose.slides/masterslide/title_style/) | Returnerar stilen för en titeltext.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/sv/aspose.slides/masterslide/body_style/) | Returnerar stilen för brödtexten.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/sv/aspose.slides/masterslide/other_style/) | Returnerar stilen för annan text.<br/>            Skrivskyddad [`ITextStyle`](/slides/python-net/sv/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/sv/aspose.slides/masterslide/layout_slides/) | Returnerar samlingen av barn-layoutbilder för denna masterbild.<br/>            Skrivskyddad [`IMasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/sv/aspose.slides/masterslide/preserve/) | Bestämmer om motsvarande master tas bort när alla bilder som följer den masteren tas bort.<br/>            Notera: Aspose.Slides kommer aldrig att självt ta bort någon oanvänd master, för att faktiskt ta bort oanvända masters anropa **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Läs/skriv **bool**. |
| [`has_depending_slides`](/slides/python-net/sv/aspose.slides/masterslide/has_depending_slides/) | Returnerar sant om det finns minst en bild som är beroende av denna masterbild.<br/>            Skrivskyddad **bool**. |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/masterslide/theme_manager/) | Returnerar temahanteraren.<br/>            Skrivskyddad [`IMasterThemeManager`](/slides/python-net/sv/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/sv/aspose.slides/masterslide/drawing_guides/) | Returnerar en samling av ritguider för masterbilden.<br/>            Skrivskyddad [`IDrawingGuidesCollection`](/slides/python-net/sv/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/sv/aspose.slides/masterslide/slide/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/sv/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/masterslide/equals/#ibaseslide) | Bestämmer om de två IBaseSlide-instanserna är lika.<br/>            Returvärdet beräknas baserat på bildens struktur och statiska innehåll.<br/>            Två bilder är lika om alla former, stilar, texter, animation och andra inställningar etc. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/masterslide/create_theme_effective/#) | Returnerar ett effektivt tema för denna bild. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Hittar första förekomsten av en form med den angivna alternativa texten. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/sv/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Skapar en ny masterbild baserad på den aktuella, applicerar ett externt tema på den <br/>            och tillämpar den skapade masterbilden på alla beroende bilder. |
| [`get_depending_slides(self)`](/slides/python-net/sv/aspose.slides/masterslide/get_depending_slides/#) | Returnerar en array med alla bilder som är beroende av denna masterbild. |

### Se även
* klass [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)
* klass [`MasterSlide`](/slides/python-net/sv/aspose.slides/masterslide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)