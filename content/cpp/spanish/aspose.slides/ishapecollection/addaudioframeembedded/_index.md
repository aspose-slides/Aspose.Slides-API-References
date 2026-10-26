---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides para C++ Referencia de API
description: Crea un nuevo marco de audio con un archivo WAV incrustado y lo agrega al final de la colección de formas. El audio incrustado se agrega a la colección Presentation.Audios.
type: docs
weight: 248
url: /es/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) método

Crea un nuevo marco de audio con un archivo WAV incrustado y lo agrega al final de la colección de formas. El audio incrustado se agrega a la colección Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo de entrada que contiene datos de audio WAV para incrustar. |

### Valor de retorno

El [IAudioFrame](../../iaudioframe/) recién creado.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) método

Crea un nuevo marco de audio y lo agrega al final de la colección de formas utilizando un objeto de audio existente de la lista Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco de audio, en puntos. |
| y | **float** | La coordenada y del nuevo marco de audio, en puntos. |
| width | **float** | El ancho del nuevo marco de audio, en puntos. |
| height | **float** | La altura del nuevo marco de audio, en puntos. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Una instancia de [IAudio](../../iaudio/) de la colección Presentation.Audios. |

### Valor de retorno

El [IAudioFrame](../../iaudioframe/) recién creado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudioFrame](../../iaudioframe/)
* Clase [Stream](../../../system.io/stream/)
* Clase [IShapeCollection](../)
* Clase [IAudio](../../iaudio/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)