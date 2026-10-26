---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Maakt een nieuw audioframe met een ingesloten WAV-bestand en voegt het toe aan de vormverzameling op de opgegeven index. Het ingesloten audio wordt toegevoegd aan de Presentation.Audios-verzameling.

### Retourwaarde

Het nieuw aangemaakte [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De index, beginnend bij nul, waarop het audioframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio_stream | **io.RawIOBase** | Een invoerstroom die WAV-audio-gegevens bevat om in te sluiten. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Maakt een nieuw audioframe en voegt het toe aan de vormverzameling op de opgegeven index met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

### Retourwaarde

Het nieuw aangemaakte [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De index, beginnend bij nul, waarop het audioframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| audio | [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio) | Een [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio)-instance uit de Presentation.Audios-verzameling om in te sluiten. |



### Zie ook
* klasse [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio)
* klasse [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)