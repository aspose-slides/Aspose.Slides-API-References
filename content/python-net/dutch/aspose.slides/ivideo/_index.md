---
title: IVideo class
second_title: Aspose.Slides voor Python via .NET API referentie
description: 
type: docs
url: /nl/aspose.slides/ivideo/
---
## IVideo klasse

Stelt een video voor die in een presentatie is ingesloten.

Het IVideo-type biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`content_type`](/slides/python-net/nl/aspose.slides/ivideo/content_type/) | Retourneert een MIME-type van een video, gecodeerd in [`IVideo.binary_data`](/slides/python-net/nl/aspose.slides/ivideo/binary_data).<br/>            Alleen-lezen **str**. |
| [`binary_data`](/slides/python-net/nl/aspose.slides/ivideo/binary_data/) | Retourneert een kopie van de gegevens van een audio. In geval van een grote hoeveelheid data overweeg het gebruik van <br/>            [`IVideo.get_stream`](/slides/python-net/nl/aspose.slides/ivideo/get_stream) methode om onnodig laden van video-gegevens in het geheugen te voorkomen <br/>            of zelfs OutOfMemoryException.<br/>            Alleen-lezen **int**[]. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/nl/aspose.slides/ivideo/get_stream/#) | Retourneert Stream stream voor lezen.<br/>            Gebruik 'using' of sluit de stream na gebruik. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)