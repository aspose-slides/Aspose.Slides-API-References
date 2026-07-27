---
title: get_RewindAudio()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Lectura bool.
type: docs
weight: 235
url: /es/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() método


Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Lectura **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Añadir marco de audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)