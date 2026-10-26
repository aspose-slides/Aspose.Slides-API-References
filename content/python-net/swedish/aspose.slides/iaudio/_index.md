---
title: IAudio class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iaudio/
---
## IAudio klass

Representerar en inbäddad ljudfil.

Typen IAudio exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`content_type`](/slides/python-net/sv/aspose.slides/iaudio/content_type/) | Returnerar en MIME-typ för ett ljud, kodad i [`IAudio.binary_data`](/slides/python-net/sv/aspose.slides/iaudio/binary_data).<br/>            Skrivskyddad **str**. |
| [`binary_data`](/slides/python-net/sv/aspose.slides/iaudio/binary_data/) | Returnerar en kopia av ett ljuds data. Vid stor mängd data bör du överväga <br/>            användning av [`IAudio.get_stream`](/slides/python-net/sv/aspose.slides/iaudio/get_stream)-metoden för att förhindra onödig laddning av ljudets<br/>            data i minnet eller till och med OutOfMemoryException.<br/>            Skrivskyddad **int**[]. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/sv/aspose.slides/iaudio/get_stream/#) | Returnerar Stream-ström för läsning.<br/>            Använd 'using' eller stäng strömmen efter användning. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)