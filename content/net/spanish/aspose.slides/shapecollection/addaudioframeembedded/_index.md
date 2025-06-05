---
title: AddAudioFrameEmbedded
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega un nuevo marco de audio con un archivo de audio incrustado al final de una colección. El archivo de audio incrustado puede ser solo un WAV. Agrega un nuevo audio a la lista Presentation.Audios.
type: docs
weight: 70
url: /es/aspose.slides/shapecollection/addaudioframeembedded/
---

## AddAudioFrameEmbedded(float, float, float, float, Stream) {#addaudioframeembedded_1}

Agrega un nuevo marco de audio con un archivo de audio incrustado al final de una colección. El archivo de audio incrustado puede ser solo un WAV. Agrega un nuevo audio a la lista Presentation.Audios.

```csharp
public IAudioFrame AddAudioFrameEmbedded(float x, float y, float width, float height, 
    Stream audio_stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | Coordenada X de un nuevo marco de audio. |
| y | Single | Coordenada Y de un nuevo marco de audio. |
| width | Single | Ancho de un nuevo marco de audio. |
| height | Single | Altura de un nuevo marco de audio. |
| audio_stream | Stream | Flujo de entrada/salida con datos de audio. |

### Valor de Retorno

Objeto AudioFrame creado.

### Ejemplos

Los siguientes ejemplos muestran cómo crear un marco de audio.

```csharp
[C#]
// Instancia una clase de presentación que representa un archivo de presentación
using (Presentation pres = new Presentation())
{
    // Obtiene la primera diapositiva
    ISlide sld = pres.Slides[0];
    // Carga el archivo de sonido wav en el flujo
    FileStream fstr = new FileStream("sampleaudio.wav", FileMode.Open, FileAccess.Read);
    // Agrega el marco de audio
    IAudioFrame audioFrame = sld.Shapes.AddAudioFrameEmbedded(50, 150, 100, 100, fstr);
    // Configura el modo de reproducción y el volumen del audio
    audioFrame.PlayMode = AudioPlayModePreset.Auto;
    audioFrame.Volume = AudioVolumeMode.Loud;
    // Escribe el archivo de PowerPoint en el disco
    pres.Save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interface [IAudioFrame](../../iaudioframe)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddAudioFrameEmbedded(float, float, float, float, IAudio) {#addaudioframeembedded}

Agrega un nuevo marco de audio con un archivo de audio incrustado al final de una colección. Utiliza el archivo de audio de la lista Presentation.Audios.

```csharp
public IAudioFrame AddAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | Coordenada X de un nuevo marco de audio. |
| y | Single | Coordenada Y de un nuevo marco de audio. |
| width | Single | Ancho de un nuevo marco de audio. |
| height | Single | Altura de un nuevo marco de audio. |
| audio | IAudio | Audio de la lista Presentation.Audios. |

### Valor de Retorno

Objeto AudioFrame creado.

### Ver También

* interface [IAudioFrame](../../iaudioframe)
* interface [IAudio](../../iaudio)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->