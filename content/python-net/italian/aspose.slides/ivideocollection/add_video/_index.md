---
title: add_video method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Aggiunge una copia di un file video da un'altra presentazione.

### Restituisce

Video aggiunto.



```python
def add_video(self, video):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/it/aspose.slides/ivideo) | Video di origine. |


## add_video(self, video_data) {#bytes}
Crea e aggiunge un video a una presentazione da un array di byte.

### Restituisce

Video aggiunto.



```python
def add_video(self, video_data):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| video_data | **bytes** | Byte del video. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea e aggiunge un video a una presentazione da uno stream.

### Restituisce

Added [`IVideo`](/slides/python-net/it/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream da cui aggiungere il file video. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/it/aspose.slides/loadingstreambehavior) | Il comportamento che sarà applicato allo stream. |



### Vedi anche
* classe [`IVideo`](/slides/python-net/it/aspose.slides/ivideo)
* classe [`IVideoCollection`](/slides/python-net/it/aspose.slides/ivideocollection)
* enumerazione [`LoadingStreamBehavior`](/slides/python-net/it/aspose.slides/loadingstreambehavior)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)