---
title: insert_audio_frame_embedded method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios.

### Devuelve

El [`IAudioFrame`](/slides/python-net/es/aspose.slides/iaudioframe) recién creado.

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se insertará el marco de audio. |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio_stream | **io.RawIOBase** | Un flujo de entrada que contiene datos de audio WAV para incrustar. |

## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios.

### Devuelve

El [`IAudioFrame`](/slides/python-net/es/aspose.slides/iaudioframe) recién creado.

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se insertará el marco de audio. |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio | [`IAudio`](/slides/python-net/es/aspose.slides/iaudio) | Una instancia [`IAudio`](/slides/python-net/es/aspose.slides/iaudio) de la colección Presentation.Audios para incrustar. |

### Ver también
* clase [`IAudio`](/slides/python-net/es/aspose.slides/iaudio)
* clase [`IAudioFrame`](/slides/python-net/es/aspose.slides/iaudioframe)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)