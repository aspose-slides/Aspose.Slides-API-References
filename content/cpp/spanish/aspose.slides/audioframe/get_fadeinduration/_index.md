---
title: get_FadeInDuration()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la duración del fundido de entrada inicial del medio en milisegundos. Lectura float.
type: docs
weight: 326
url: /es/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() método


Especifica la duración del fundido de entrada inicial del medio en milisegundos. Lectura **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Añadir marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer la duración del fundido inicial a 200 ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)