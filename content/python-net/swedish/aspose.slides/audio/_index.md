---
title: Audio class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/audio/
---
## Audio klass

Representerar en inbäddad ljudfil.

Audio-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`content_type`](/slides/python-net/sv/aspose.slides/audio/content_type/) | Returnerar en MIME-typ för en ljudfil, kodad i [`Audio.binary_data`](/slides/python-net/sv/aspose.slides/audio/binary_data).<br/>            Skrivskyddad **str**. |
| [`binary_data`](/slides/python-net/sv/aspose.slides/audio/binary_data/) | Returnerar en kopia av en ljudfils data. Vid stora datamängder bör du <br/>            använda [`Audio.get_stream`](/slides/python-net/sv/aspose.slides/audio/get_stream) metod för att förhindra onödig laddning av ljudens<br/>            data till minnet eller till och med OutOfMemoryException.<br/>            Skrivskyddad **int**[]. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/sv/aspose.slides/audio/get_stream/#) | Returnerar Stream stream för läsning.<br/>            Använd 'using' eller stäng strömmen efter användning. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)