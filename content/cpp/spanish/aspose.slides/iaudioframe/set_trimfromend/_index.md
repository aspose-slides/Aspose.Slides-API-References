---
title: set_TrimFromEnd()
second_title: Aspose.Slides para la referencia de API de C++
description: Especifica la duración del tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Escriba float.
type: docs
weight: 443
url: /es/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) método


Especifica la duración del tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Escriba **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Añadir marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer el tiempo de recorte al final 2 segundos
audioFrame->set_TrimFromEnd(2000.0f);
```

## Véase también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)