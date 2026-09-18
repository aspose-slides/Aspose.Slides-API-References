---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides dla Pythona via .NET referencja API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów w określonym indeksie. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

### Zwraca

Nowo utworzony [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym ma zostać wstawiona ramka audio. |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| audio_stream | **io.RawIOBase** | Strumień wejściowy zawierający dane audio WAV do osadzenia. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów w określonym indeksie, używając istniejącego obiektu audio z listy Presentation.Audios.

### Zwraca

Nowo utworzony [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym ma zostać wstawiona ramka audio. |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| audio | [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio) | Instancja [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio) z kolekcji Presentation.Audios do osadzenia. |



### Zobacz także
* klasa [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio)
* klasa [`IAudioFrame`](/slides/python-net/pl/aspose.slides/iaudioframe)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)