---
title: InsertAudioFrameEmbedded()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios.
type: docs
weight: 261
url: /es/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el marco de audio. |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo de entrada que contiene datos de audio WAV para incrustar. |

### Valor de retorno

El [IAudioFrame](../../iaudioframe/) recién creado.

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) method


Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el marco de audio. |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Una instancia [IAudio](../../iaudio/) de la colección Presentation.Audios para incrustar. |

### Valor de retorno

El [IAudioFrame](../../iaudioframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)