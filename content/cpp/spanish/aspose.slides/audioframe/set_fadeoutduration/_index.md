---
title: set_FadeOutDuration()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la duración temporal para el fundido de salida final del medio en milisegundos. Escriba float.
type: docs
weight: 365
url: /es/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) método


Especifica la duración temporal para el fundido de salida final del medio en milisegundos. Escriba **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## Observaciones


Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar cuadro de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer la duración del fundido final a 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)