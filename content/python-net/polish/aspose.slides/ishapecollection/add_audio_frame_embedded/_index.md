---
title: add_audio_frame_embedded method
second_title: Aspose.Slides dla Pythona poprzez .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Tworzy nową ramkę dźwiękową z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

### Zwraca

The newly created [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | **io.RawIOBase** | An input stream containing WAV audio data to embed. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Tworzy nową ramkę dźwiękową i dodaje ją na koniec kolekcji kształtów, korzystając z istniejącego obiektu audio z listy Presentation.Audios.

### Zwraca

The newly created [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio) | An [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio) instance from the Presentation.Audios collection. |



### Zobacz także
* klasa [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio)
* klasa [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)