---
title: get_FadeOutDuration()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la duración del desvanecimiento final del medio en milisegundos. Lectura float.
type: docs
weight: 352
url: /es/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() método

Especifica la duración del desvanecimiento final del medio en milisegundos. Lectura **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Observaciones

Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer la duración del desvanecimiento final a 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)