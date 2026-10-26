---
title: set_PlayAcrossSlides()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el audio se reproduce a través de las diapositivas. Escribe bool.
type: docs
weight: 222
url: /es/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) método

Determina si el audio se reproduce a través de las diapositivas. Escribe **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Añadir marco de audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Configurar audio para reproducirse a través de las diapositivas
audioFrame->set_PlayAcrossSlides(true);

// Configurar audio para rebobinar automáticamente al inicio después de reproducir
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Véase también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)