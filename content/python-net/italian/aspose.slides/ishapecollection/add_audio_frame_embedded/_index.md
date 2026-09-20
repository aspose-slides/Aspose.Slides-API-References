---
title: add_audio_frame_embedded method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della
            collezione di forme. L'audio incorporato viene aggiunto alla collezione Presentation.Audios.

### Restituisce

Il nuovo [`IAudioFrame`](/slides/python-net/it/aspose.slides/iaudioframe) creato.



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| audio_stream | **io.RawIOBase** | Un flusso di input contenente dati audio WAV da incorporare. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Crea un nuovo frame audio e lo aggiunge alla fine della collezione di forme utilizzando un oggetto audio esistente dalla lista Presentation.Audios.

### Restituisce

Il nuovo [`IAudioFrame`](/slides/python-net/it/aspose.slides/iaudioframe) creato.



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame audio, in punti. |
| y | **float** | La coordinata y del nuovo frame audio, in punti. |
| width | **float** | La larghezza del nuovo frame audio, in punti. |
| height | **float** | L'altezza del nuovo frame audio, in punti. |
| audio | [`IAudio`](/slides/python-net/it/aspose.slides/iaudio) | Un'istanza [`IAudio`](/slides/python-net/it/aspose.slides/iaudio) dalla collezione Presentation.Audios. |



### Vedi anche
* classe [`IAudio`](/slides/python-net/it/aspose.slides/iaudio)
* classe [`IAudioFrame`](/slides/python-net/it/aspose.slides/iaudioframe)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)