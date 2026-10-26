---
title: IAudio class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iaudio/
---
## IAudio class

Stelt een ingebed audiobestand voor.

Het IAudio-type geeft de volgende leden vrij:

## Properties

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/nl/aspose.slides/iaudio/content_type/) | Retourneert een MIME-type van een audio, gecodeerd in [`IAudio.binary_data`](/slides/python-net/nl/aspose.slides/iaudio/binary_data).<br/>            Alleen-lezen **str**. |
| [`binary_data`](/slides/python-net/nl/aspose.slides/iaudio/binary_data/) | Retourneert een kopie van de audio-gegevens. Bij een grote hoeveelheid gegevens, overweeg <br/>            het gebruik van de [`IAudio.get_stream`](/slides/python-net/nl/aspose.slides/iaudio/get_stream)-methode om onnodig laden van audio-gegevens<br/>            in het geheugen of zelfs een OutOfMemoryException te voorkomen.<br/>            Alleen-lezen **int**[]. |

## Methods

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/nl/aspose.slides/iaudio/get_stream/#) | Retourneert een Stream-stroom voor lezen.<br/>            Gebruik 'using' of sluit de stroom na gebruik. |


### See Also
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)