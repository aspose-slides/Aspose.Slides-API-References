---
title: BaseSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/baseslide/
---
## BaseSlide klass

Representerar gemensam data för alla bildtyper.

BaseSlide-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/baseslide/shapes/) | Returnerar formerna på en bild.<br/>            Skrivskyddad [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/baseslide/controls/) | Returnerar samlingen av ActiveX-kontroller på en bild.<br/>            Skrivskyddad [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/baseslide/name/) | Returnerar eller anger namn på en bild.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/baseslide/slide_id/) | Returnerar ID för en bild.<br/>            Skrivskyddad **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/baseslide/custom_data/) | Returnerar bildens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/baseslide/timeline/) | Returnerar animations-tidslinjeobjekt.<br/>            Skrivskyddad [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/baseslide/slide_show_transition/) | Returnerar Transition-objektet som innehåller information om<br/>            hur den angivna bilden går vidare under en bildspelsvisning.<br/>            Skrivskyddad [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/baseslide/background/) | Returnerar bildens bakgrund.<br/>            Skrivskyddad [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/baseslide/hyperlink_queries/) | Ger enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/baseslide/show_master_shapes/) | Anger om former på mastern ska visas på bilder eller inte.<br/>            För själva mastern returnerar denna egenskap alltid `false`.<br/>            Läs/skriv **bool**. |
| [`presentation`](/slides/python-net/sv/aspose.slides/baseslide/presentation/) | Returnerar IPresentation-gränssnittet.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/sv/aspose.slides/baseslide/slide/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/sv/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Sammanfogar körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/baseslide/equals/#ibaseslide) | Bestämmer om de två IBaseSlide-instanserna är lika.<br/>            Returnerat värde beräknas baserat på bildens struktur och statiska innehåll.<br/>            Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. nuvarande datumvärde i datumplatshållare. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/baseslide/create_theme_effective/#) | Returnerar ett effektivt tema för denna bild. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Hittar första förekomsten av en form med den angivna alternativa texten. |


### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)