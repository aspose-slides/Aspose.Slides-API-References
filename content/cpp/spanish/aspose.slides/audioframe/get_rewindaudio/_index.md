---
title: get_RewindAudio()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el audio se rebobina automáticamente al inicio después de reproducirse. Lectura bool.
type: docs
weight: 235
url: /es/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() método


Determina si el audio se rebobina automáticamente al inicio después de reproducirse. Lectura **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Agregar marco de audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Establecer audio para reproducir en todas las diapositivas
audioFrame->set_PlayAcrossSlides(true);

// Establecer audio para rebobinar automáticamente al inicio después de reproducir
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Ver también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)