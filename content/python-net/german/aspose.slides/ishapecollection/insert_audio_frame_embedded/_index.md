---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn an der angegebenen Position in die Shape-Sammlung ein. Der eingebettete Audio wird zur Presentation.Audios-Sammlung hinzugefügt.

### Rückgabewert

Das neu erstellte [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | **io.RawIOBase** | An input stream containing WAV audio data to embed. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Position in die Shape-Sammlung ein, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

### Rückgabewert

Das neu erstellte [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [`IAudio`](/slides/python-net/de/aspose.slides/iaudio) | An [`IAudio`](/slides/python-net/de/aspose.slides/iaudio) instance from the Presentation.Audios collection to embed. |



### Siehe auch
* Klasse [`IAudio`](/slides/python-net/de/aspose.slides/iaudio)
* Klasse [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)