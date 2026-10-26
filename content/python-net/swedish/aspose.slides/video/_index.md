---
title: Video class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/video/
---
## Video-klass

Representerar en bild som är inbäddad i en presentation.

Video-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`content_type`](/slides/python-net/sv/aspose.slides/video/content_type/) | Returnerar en MIME-typ för en video, kodad i [`Video.binary_data`](/slides/python-net/sv/aspose.slides/video/binary_data).<br/>            Skrivskyddad **str**. |
| [`binary_data`](/slides/python-net/sv/aspose.slides/video/binary_data/) | Returnerar en kopia av en ljuddata. Vid stora mängder data bör du överväga att använda <br/>            [`Video.get_stream`](/slides/python-net/sv/aspose.slides/video/get_stream)-metoden för att förhindra onödig inläsning av video-data i minnet <br/>            eller till och med OutOfMemoryException.<br/>            Skrivskyddad **int**[]. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/sv/aspose.slides/video/get_stream/#) | Returnerar Stream-ström för läsning.<br/>            Använd 'using' eller stäng strömmen efter användning. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)