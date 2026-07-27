---
title: InsertAudioFrameEmbedded()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección Presentation::get_Audios."
type: docs
weight: 300
url: /es/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) método

Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el marco de audio. |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | La anchura del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Una secuencia de entrada que contiene datos de audio WAV para incrustar. |

### Valor devuelto

El [IAudioFrame](../../iaudioframe/) recién creado.

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) método

Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado utilizando un objeto de audio existente de la lista [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el marco de audio. |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | La anchura del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Una instancia [IAudio](../../iaudio/) de la colección [Presentation::get_Audios](../../presentation/get_audios/) para incrustar. |

### Valor devuelto

El [IAudioFrame](../../iaudioframe/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudioFrame](../../iaudioframe/)
* Clase [Stream](../../../system.io/stream/)
* Clase [ShapeCollection](../)
* Clase [IAudio](../../iaudio/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)