---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Crea un nuovo frame audio con un file WAV incorporato e lo inserisce nella collezione di forme all'indice specificato. L'audio incorporato viene aggiunto alla collezione Presentation.Audios.

### Restituisce

Il nuovo [`IAudioFrame`](/slides/python-net/it/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame audio. |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| audio_stream | **io.RawIOBase** | Uno stream di input contenente dati audio WAV da incorporare. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Crea un nuovo frame audio e lo inserisce nella collezione di forme all'indice specificato usando un oggetto audio esistente dalla lista Presentation.Audios.

### Restituisce

Il nuovo [`IAudioFrame`](/slides/python-net/it/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame audio. |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| audio | [`IAudio`](/slides/python-net/it/aspose.slides/iaudio) | Un'istanza [`IAudio`](/slides/python-net/it/aspose.slides/iaudio) della collezione Presentation.Audios da incorporare. |



### Vedi anche
* classe [`IAudio`](/slides/python-net/it/aspose.slides/iaudio)
* classe [`IAudioFrame`](/slides/python-net/it/aspose.slides/iaudioframe)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)