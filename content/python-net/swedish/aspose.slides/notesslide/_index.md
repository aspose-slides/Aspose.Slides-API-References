---
title: NotesSlide class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/notesslide/
---
## NotesSlide klass

Representerar en notes-bild i en presentation.

**Arv:**[`NotesSlide`](/slides/python-net/sv/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)

NotesSlide-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shapes`](/slides/python-net/sv/aspose.slides/notesslide/shapes/) | Returnerar formerna på en bild.<br/>            Skrivskyddad [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/sv/aspose.slides/notesslide/controls/) | Returnerar samlingen av ActiveX-kontroller på en bild.<br/>            Skrivskyddad [`IControlCollection`](/slides/python-net/sv/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/sv/aspose.slides/notesslide/name/) | Returnerar eller anger namnet på en bild.<br/>            Läs/skriv **str**. |
| [`slide_id`](/slides/python-net/sv/aspose.slides/notesslide/slide_id/) | Returnerar ID-t för en bild.<br/>            Skrivskyddad **int**. |
| [`custom_data`](/slides/python-net/sv/aspose.slides/notesslide/custom_data/) | Returnerar bildens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/sv/aspose.slides/notesslide/timeline/) | Returnerar animations-tidslinjeobjektet.<br/>            Skrivskyddad [`IAnimationTimeLine`](/slides/python-net/sv/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/sv/aspose.slides/notesslide/slide_show_transition/) | Returnerar Transition-objektet som innehåller information om<br/>            hur den angivna bilden avancerar under ett bildspel.<br/>            Skrivskyddad [`ISlideShowTransition`](/slides/python-net/sv/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/sv/aspose.slides/notesslide/background/) | Returnerar bildens bakgrund.<br/>            Skrivskyddad [`IBackground`](/slides/python-net/sv/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/sv/aspose.slides/notesslide/hyperlink_queries/) | Ger enkel åtkomst till inbäddade hyperlänkar.<br/>            Skrivskyddad [`IHyperlinkQueries`](/slides/python-net/sv/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/sv/aspose.slides/notesslide/show_master_shapes/) | Anger om former på huvudbilden ska visas på bilder eller inte.<br/>            Läs/skriv **bool**. |
| [`presentation`](/slides/python-net/sv/aspose.slides/notesslide/presentation/) | Returnerar IPresentation-gränssnittet.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/sv/aspose.slides/notesslide/header_footer_manager/) | Returnerar HeaderFooter-hanteraren för notes-bilden.<br/>            Skrivskyddad [`INotesSlideHeaderFooterManager`](/slides/python-net/sv/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/sv/aspose.slides/notesslide/notes_text_frame/) | Returnerar ett TextFrame med notes-texten om det finns någon.<br/>            Skrivskyddad [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/sv/aspose.slides/notesslide/theme_manager/) | Returnerar den överordnade temahanteraren.<br/>            Skrivskyddad [`IOverrideThemeManager`](/slides/python-net/sv/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/sv/aspose.slides/notesslide/parent_slide/) | Returnerar föräldrabilden.<br/>            Skrivskyddad [`ISlide`](/slides/python-net/sv/aspose.slides/islide). |
| [`slide`](/slides/python-net/sv/aspose.slides/notesslide/slide/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/sv/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Sammanfogar runs med samma formatering i alla stycken i alla accepterade former. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/sv/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Sammanfogar runs med samma formatering i alla stycken i alla accepterade former. |
| [`equals(self, slide)`](/slides/python-net/sv/aspose.slides/notesslide/equals/#ibaseslide) | Bestämmer om de två IBaseSlide-instanserna är lika.<br/>            Returvärdet beräknas baserat på bildens struktur och statiska innehåll.<br/>            Två bilder är lika om alla former, stilar, texter, animation och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifieringsvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i datum-platshållare. |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides/notesslide/create_theme_effective/#) | Returnerar ett effektivt tema för denna bild. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/sv/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Hittar första förekomst av en form med den angivna alternativa texten. |


### Se även
* klass [`BaseSlide`](/slides/python-net/sv/aspose.slides/baseslide)
* klass [`NotesSlide`](/slides/python-net/sv/aspose.slides/notesslide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)