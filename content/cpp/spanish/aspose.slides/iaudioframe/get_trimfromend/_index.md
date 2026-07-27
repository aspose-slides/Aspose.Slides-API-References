---
title: get_TrimFromEnd()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la duración de tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Solo lectura float.
type: docs
weight: 430
url: /es/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() método


Especifica la duración de tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Solo lectura **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer el tiempo de recorte final a 2 segundos
audioFrame->set_TrimFromEnd(2000.0f);
```

## Véase también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)