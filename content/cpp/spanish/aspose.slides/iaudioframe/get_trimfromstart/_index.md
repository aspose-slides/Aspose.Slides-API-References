---
title: get_TrimFromStart()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la duración de tiempo que se eliminará del principio del medio durante la reproducción, en milisegundos. Lectura float.
type: docs
weight: 404
url: /es/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() método


Especifica la duración de tiempo que se eliminará del principio del medio durante la reproducción, en milisegundos. Lectura **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer el tiempo de recorte inicial a 1.5 segundos
audioFrame->set_TrimFromStart(1500.0f);
```

## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)