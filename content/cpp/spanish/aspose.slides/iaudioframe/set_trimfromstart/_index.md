---
title: set_TrimFromStart()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la duración de tiempo que se eliminará del comienzo del medio durante la reproducción, en milisegundos. Escriba float.
type: docs
weight: 417
url: /es/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) método


Especifica la duración de tiempo que se eliminará del comienzo del medio durante la reproducción, en milisegundos. Escriba **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Añadir marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer el tiempo de recorte inicial a 1.5 segundos
audioFrame->set_TrimFromStart(1500.0f);
```

## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)