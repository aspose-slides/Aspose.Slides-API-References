---
title: get_TrimFromEnd()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la duración de tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Lee float.
type: docs
weight: 430
url: /es/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() método


Especifica la duración de tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Lee **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer el tiempo de recorte al final 2 segundos
audioFrame->set_TrimFromEnd(2000.0f);
```

## Ver también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)