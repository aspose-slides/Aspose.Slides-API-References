---
title: add_audio method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Aggiunge una copia di un file audio da un'altra presentazione.

### Restituisce

Audio aggiunto.



```python
def add_audio(self, audio):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/it/aspose.slides/iaudio) | Audio di origine. |


## add_audio(self, stream) {#iorawiobase}
Crea e aggiunge un audio a una presentazione da stream.

### Restituisce

Audio aggiunto.



```python
def add_audio(self, stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream da cui aggiungere l'audio. |


## add_audio(self, audio_data) {#bytes}
Crea e aggiunge un audio a una presentazione da un array di byte.

### Restituisce

Audio aggiunto.



```python
def add_audio(self, audio_data):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| audio_data | **bytes** | Byte dell'audio. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea e aggiunge un audio a una presentazione da stream.

### Restituisce

Audio aggiunto.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream da cui aggiungere l'audio video. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/it/aspose.slides/loadingstreambehavior) | Il comportamento che verrà applicato allo stream. |



### Vedi anche
* classe [`AudioCollection`](/slides/python-net/it/aspose.slides/audiocollection)
* classe [`IAudio`](/slides/python-net/it/aspose.slides/iaudio)
* enumerazione [`LoadingStreamBehavior`](/slides/python-net/it/aspose.slides/loadingstreambehavior)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)