---
title: add_video method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Agrega una copia de un archivo de video de otra presentación.

### Devuelve

Video agregado.



```python
def add_video(self, video):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/es/aspose.slides/ivideo) | Video de origen. |


## add_video(self, video_data) {#bytes}
Crea y agrega un video a una presentación a partir de una matriz de bytes.

### Devuelve

Video agregado.



```python
def add_video(self, video_data):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| video_data | **bytes** | Bytes del video. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea y agrega un video a una presentación desde un flujo.

### Devuelve

Agregado [`IVideo`](/slides/python-net/es/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo del cual agregar el archivo de video. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior) | El comportamiento que se aplicará al flujo. |



### Ver también
* clase [`IVideo`](/slides/python-net/es/aspose.slides/ivideo)
* enumeración [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior)
* clase [`VideoCollection`](/slides/python-net/es/aspose.slides/videocollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)