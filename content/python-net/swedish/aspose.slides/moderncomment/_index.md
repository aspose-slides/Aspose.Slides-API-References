---
title: ModernComment class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/moderncomment/
---
## ModernComment klass

Representerar en kommentar på en bild.

**Arv:**[`ModernComment`](/slides/python-net/sv/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/sv/aspose.slides/comment)

ModernComment-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`text`](/slides/python-net/sv/aspose.slides/moderncomment/text/) | Returnerar eller anger den rena texten för en bildkommentar.<br/>            Läs/skriv **str**. |
| [`created_time`](/slides/python-net/sv/aspose.slides/moderncomment/created_time/) | Returnerar eller anger tiden för när kommentaren skapades.<br/>            Att sätta denna egenskap till **System.DateTime** innebär att ingen kommentarstid är angiven.<br/>            Läs/skriv **System.DateTime**. |
| [`slide`](/slides/python-net/sv/aspose.slides/moderncomment/slide/) | Returnerar eller anger den överordnade bilden för en kommentar.<br/>            Läs-endast [`ISlide`](/slides/python-net/sv/aspose.slides/islide). |
| [`author`](/slides/python-net/sv/aspose.slides/moderncomment/author/) | Returnerar författaren till en kommentar.<br/>            Läs-endast [`ICommentAuthor`](/slides/python-net/sv/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/sv/aspose.slides/moderncomment/position/) | Returnerar eller anger positionen för en kommentar på en bild.<br/>            Läs/skriv **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/sv/aspose.slides/moderncomment/parent_comment/) | Returnerar eller anger föräldrakommentar.<br/>            Läs/skriv [`IComment`](/slides/python-net/sv/aspose.slides/icomment). |
| [`shape`](/slides/python-net/sv/aspose.slides/moderncomment/shape/) | Returnerar en form som är associerad med kommentaren.<br/>            Läs-endast [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/sv/aspose.slides/moderncomment/text_selection_start/) | Returnerar eller anger startpositionen för textmarkeringen i textram om kommentaren är associerad med AutoShape.<br/>            Läs/skriv **int**. |
| [`text_selection_length`](/slides/python-net/sv/aspose.slides/moderncomment/text_selection_length/) | Returnerar eller anger längden på textmarkeringen i textram om kommentaren är associerad med AutoShape.<br/>            Läs/skriv **int**. |
| [`status`](/slides/python-net/sv/aspose.slides/moderncomment/status/) | Returnerar eller anger statusen för kommentaren.<br/>            Läs/skriv [`ModernCommentStatus`](/slides/python-net/sv/aspose.slides/moderncommentstatus). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`remove(self)`](/slides/python-net/sv/aspose.slides/moderncomment/remove/#) | Tar bort kommentaren och alla dess svar från den överordnade samlingen. |

### Se även
* klass [`Comment`](/slides/python-net/sv/aspose.slides/comment)
* klass [`ModernComment`](/slides/python-net/sv/aspose.slides/moderncomment)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)