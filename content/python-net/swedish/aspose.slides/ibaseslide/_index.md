---
title: IBaseSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ibaseslide/
---
## IBaseSlide klass

Representerar gemensam data för alla bildtyper.

IBaseSlide-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/ibaseslide/shapes/) | Returnerar formerna på en bild.<br/>            Skrivskyddad [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/ibaseslide/controls/) | Returnerar samlingen av ActiveX-kontroller på en bild.<br/>            Skrivskyddad [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/ibaseslide/name/) | Returnerar eller sätter namnet på en bild.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/ibaseslide/slide_id/) | Returnerar ID:t för en bild.<br/>            Skrivskyddad **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/ibaseslide/custom_data/) | Returnerar bildens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/ibaseslide/timeline/) | Returnerar animations tidslinje-objekt.<br/>            Skrivskyddad [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/ibaseslide/slide_show_transition/) | Returnerar TransitionEx-objektet som innehåller information om<br/>            hur den angivna bilden avancerar under en presentation.<br/>            Skrivskyddad [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/ibaseslide/background/) | Returnerar bildens bakgrund.<br/>            Skrivskyddad [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/ibaseslide/hyperlink_queries/) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/ibaseslide/show_master_shapes/) | Anger om former på masterbilden ska visas på bilder eller inte.<br/>            För själva masterbilden returnerar denna egenskap alltid `false`.<br/>            Läs/skriv **bool**. |
| [`slide`](/slides/python-net/sv/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/ibaseslide/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Hittar första förekomsten av en form med den angivna alternativa texten. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Slår ihop körningar med samma formatering i alla stycken i alla acceptabla former. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/ibaseslide/equals/#ibaseslide) | Bestämmer om de två IBaseSlide-instanserna är lika.<br/>            Returnerat värde beräknas baserat på bildens struktur och statiska innehåll.<br/>            Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i datumplatshållare. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)