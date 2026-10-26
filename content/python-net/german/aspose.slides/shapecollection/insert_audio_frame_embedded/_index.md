---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn in die Shape-Sammlung an der angegebenen Position ein. Das eingebettete Audio wird zur Presentation.Audios-Sammlung hinzugefügt.

### Rückgabewert

Das neu erstellte [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames in Punkten. |
| audio_stream | **io.RawIOBase** | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Erstellt einen neuen Audio-Frame und fügt ihn in die Shape-Sammlung an der angegebenen Position ein, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

### Rückgabewert

Das neu erstellte [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames in Punkten. |
| audio | [`IAudio`](/slides/python-net/de/aspose.slides/iaudio) | Eine [`IAudio`](/slides/python-net/de/aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Sammlung, die eingebettet werden soll. |



### Siehe auch
* Klasse [`IAudio`](/slides/python-net/de/aspose.slides/iaudio)
* Klasse [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)