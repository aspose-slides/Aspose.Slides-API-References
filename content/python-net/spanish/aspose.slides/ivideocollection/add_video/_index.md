---
title: add_video method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Agrega una copia de un archivo de video de otra presentación.

### Retorno

Video añadido.



```python
def add_video(self, video):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/es/aspose.slides/ivideo) | Video fuente. |


## add_video(self, video_data) {#bytes}
Crea y agrega un video a una presentación desde una matriz de bytes.

### Retorno

Video añadido.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video_data | **bytes** | Bytes del video. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea y agrega un video a una presentación desde un flujo.

### Retorno

Añadido [`IVideo`](/slides/python-net/es/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo del que se agregará el archivo de video. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior) | El comportamiento que se aplicará al flujo. |



### Ver también
* class [`IVideo`](/slides/python-net/es/aspose.slides/ivideo)
* class [`IVideoCollection`](/slides/python-net/es/aspose.slides/ivideocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)