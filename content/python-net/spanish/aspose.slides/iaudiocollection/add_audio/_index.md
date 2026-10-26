---
title: add_audio method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Añade una copia de un archivo de audio de otra presentación.

### Returns
Audio añadido.



```python
def add_audio(self, audio):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/es/aspose.slides/iaudio) | Audio fuente. |


## add_audio(self, stream) {#iorawiobase}
Crea y añade un audio a una presentación desde un stream.

### Returns
Audio añadido.



```python
def add_audio(self, stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream desde el cual añadir el audio. |


## add_audio(self, audio_data) {#bytes}
Crea y añade un audio a una presentación a partir de un arreglo de bytes.

### Returns
Audio añadido.



```python
def add_audio(self, audio_data):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| audio_data | **bytes** | Bytes de audio. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea y añade un audio a una presentación desde un stream.

### Returns
Audio añadido.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream desde el cual añadir el audio del video. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior) | El comportamiento que se aplicará al stream. |



### See Also
* class [`IAudio`](/slides/python-net/es/aspose.slides/iaudio)
* class [`IAudioCollection`](/slides/python-net/es/aspose.slides/iaudiocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/es/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)