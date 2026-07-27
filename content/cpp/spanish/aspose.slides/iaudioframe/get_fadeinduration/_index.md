---
title: get_FadeInDuration()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la duración de tiempo para el fundido de entrada inicial de los medios en milisegundos. Lectura float.
type: docs
weight: 326
url: /es/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() método


Especifica la duración de tiempo para el fundido de entrada inicial de los medios en milisegundos. Lectura **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## Observaciones


Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer la duración del fundido inicial a 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)