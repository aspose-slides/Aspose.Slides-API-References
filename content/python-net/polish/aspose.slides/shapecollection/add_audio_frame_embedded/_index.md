---
title: add_audio_frame_embedded method
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Tworzy nową ramkę dźwiękową z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

### Zwraca

Nowo utworzony [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki dźwiękowej, w punktach. |
| y | **float** | Współrzędna y nowej ramki dźwiękowej, w punktach. |
| width | **float** | Szerokość nowej ramki dźwiękowej, w punktach. |
| height | **float** | Wysokość nowej ramki dźwiękowej, w punktach. |
| audio_stream | **io.RawIOBase** | Strumień wejściowy zawierający dane audio WAV do osadzenia. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Tworzy nową ramkę dźwiękową i dodaje ją na koniec kolekcji kształtów, używając istniejącego obiektu audio z listy Presentation.Audios.

### Zwraca

Nowo utworzony [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki dźwiękowej, w punktach. |
| y | **float** | Współrzędna y nowej ramki dźwiękowej, w punktach. |
| width | **float** | Szerokość nowej ramki dźwiękowej, w punktach. |
| height | **float** | Wysokość nowej ramki dźwiękowej, w punktach. |
| audio | [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio) | Instancja [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio) z kolekcji Presentation.Audios. |



### Zobacz także
* klasa [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio)
* klasa [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)