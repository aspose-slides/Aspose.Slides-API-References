---
title: InsertAudioFrameEmbedded
second_title: Referencia de la API de Aspose.Slides para .NET
description: Inserte un AudioFrame con un archivo de audio incrustado. El sonido del archivo de audio incrustado solo puede ser WAV.
type: docs
weight: 280
url: /es/net/aspose.slides/shapecollection/insertaudioframeembedded/
---
## InsertAudioFrameEmbedded(int, float, float, float, float, Stream) {#insertaudioframeembedded_1}

Inserte un AudioFrame con un archivo de audio incrustado. El sonido del archivo de audio incrustado solo puede ser WAV.

```csharp
public IAudioFrame InsertAudioFrameEmbedded(int index, float x, float y, float width, float height, 
    Stream audio_stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero en el que se debe insertar el valor. |
| x | Single | Coordenada X de un nuevo cuadro de audio. |
| y | Single | Coordenada Y de un nuevo cuadro de audio. |
| width | Single | Ancho de un nuevo cuadro de audio. |
| height | Single | Altura de un nuevo cuadro de audio. |
| audio_stream | Stream | Transmisión de audio. |

### Valor_devuelto

Objeto AudioFrame creado.

### Ver también

* interface [IAudioFrame](../../iaudioframe)
* class [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* asamblea [Aspose.Slides](../../../)

---

## InsertAudioFrameEmbedded(int, float, float, float, float, IAudio) {#insertaudioframeembedded}

Inserta un AudioFrame con un archivo de audio incrustado. Utiliza un archivo de audio de Presentation.Audios list.

```csharp
public IAudioFrame InsertAudioFrameEmbedded(int index, float x, float y, float width, float height, 
    IAudio audio)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero en el que se debe insertar el valor. |
| x | Single | Coordenada X de un nuevo cuadro de audio. |
| y | Single | Coordenada Y de un nuevo cuadro de audio. |
| width | Single | Ancho de un nuevo cuadro de audio. |
| height | Single | Altura de un nuevo cuadro de audio. |
| audio | IAudio | Audio de la lista Presentation.Audios. |

### Valor_devuelto

Objeto AudioFrame creado.

### Ver también

* interface [IAudioFrame](../../iaudioframe)
* interface [IAudio](../../iaudio)
* class [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->