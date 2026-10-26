---
title: add_audio_frame_embedded method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der
Formensammlung hinzu. Das eingebettete Audio wird zur Presentation.Audios-Sammlung hinzugefügt.

### Rückgabe

Der neu erstellte [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio_stream | **io.RawIOBase** | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Erstellt einen neuen Audio-Frame und fügt ihn am Ende der Formensammlung mithilfe eines
vorhandenen Audio-Objekts aus der Presentation.Audios-Liste hinzu.

### Rückgabe

Der neu erstellte [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio | [`IAudio`](/slides/python-net/de/aspose.slides/iaudio) | Eine [`IAudio`](/slides/python-net/de/aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Sammlung. |



### Siehe auch
* Klasse [`IAudio`](/slides/python-net/de/aspose.slides/iaudio)
* Klasse [`IAudioFrame`](/slides/python-net/de/aspose.slides/iaudioframe)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)