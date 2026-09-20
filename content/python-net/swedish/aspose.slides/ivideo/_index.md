---
title: IVideo class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ivideo/
---
## IVideo klass

Representerar en video som är inbäddad i en presentation.

IVideo-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/sv/aspose.slides/ivideo/content_type/) | Returnerar en MIME-typ för en video, kodad i [`IVideo.binary_data`](/slides/python-net/sv/aspose.slides/ivideo/binary_data).<br/>            Skrivskyddad **str**. |
| [`binary_data`](/slides/python-net/sv/aspose.slides/ivideo/binary_data/) | Returnerar en kopia av en ljuddata. Vid stora mängder data bör du överväga att använda <br/>            [`IVideo.get_stream`](/slides/python-net/sv/aspose.slides/ivideo/get_stream) metoden för att förhindra onödig inläsning av videoens data i minnet <br/>            eller till och med OutOfMemoryException.<br/>            Skrivskyddad **int**[]. |

## Metoder

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/sv/aspose.slides/ivideo/get_stream/#) | Returnerar en Stream för läsning.<br/>            Använd 'using' eller stäng strömmen efter användning. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)