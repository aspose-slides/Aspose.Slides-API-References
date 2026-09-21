---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het in de vormverzameling in op de opgegeven index. Het ingesloten audio-bestand wordt toegevoegd aan de Presentation.Audios-verzameling.

### Retourwaarde

Het nieuw aangemaakte [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | **io.RawIOBase** | An input stream containing WAV audio data to embed. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Maakt een nieuw audio-frame en voegt het in de vormverzameling in op de opgegeven index met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

### Retourwaarde

Het nieuw aangemaakte [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio) | An [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio) instance from the Presentation.Audios collection to embed. |



### Zie ook
* klasse [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio)
* klasse [`IAudioFrame`](/slides/python-net/nl/aspose.slides/iaudioframe)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)