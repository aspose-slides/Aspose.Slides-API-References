---
title: add_audio method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Añade una copia de un archivo de audio de otra presentación.

### Devuelve

Audio añadido.



```python
def add_audio(self, audio):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/es/aspose.slides/iaudio) | Audio de origen. |


## add_audio(self, stream) {#iorawiobase}
Crea y añade un audio a una presentación desde un flujo.

### Devuelve

Audio añadido.



```python
def add_audio(self, stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo del cual añadir audio. |


## add_audio(self, audio_data) {#bytes}
Crea y añade un audio a una presentación desde una matriz de bytes.

### Devuelve

Audio añadido.



```python
def add_audio(self, audio_data):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| audio_data | **bytes** | Bytes de audio. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea y añade un audio a una presentación desde un flujo.

### Devuelve

Audio añadido.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo del cual añadir audio de vídeo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior) | El comportamiento que se aplicará al flujo. |



### Ver también
* clase [`AudioCollection`](/slides/python-net/es/aspose.slides/audiocollection)
* clase [`IAudio`](/slides/python-net/es/aspose.slides/iaudio)
* enumeración [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)