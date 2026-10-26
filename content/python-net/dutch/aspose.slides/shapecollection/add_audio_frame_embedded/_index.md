---
title: add_audio_frame_embedded method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Maakt een nieuw audioframe met een ingesloten WAV-bestand en voegt het toe aan het einde van de vormverzameling. De ingesloten audio wordt toegevoegd aan de Presentation.Audios-verzameling.

### Retour
Het nieuw aangemaakte [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio_stream | **io.RawIOBase** | Een invoerstroom die WAV-audiogegevens bevat om in te sluiten. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Maakt een nieuw audioframe en voegt het toe aan het einde van de vormverzameling met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

### Retour
Het nieuw aangemaakte [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio | [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio) | Een [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio)-instantie uit de Presentation.Audios-verzameling. |



### Zie ook
* klasse [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio)
* klasse [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)