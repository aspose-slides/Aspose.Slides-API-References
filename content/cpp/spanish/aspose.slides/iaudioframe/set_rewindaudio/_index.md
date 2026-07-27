---
title: set_RewindAudio()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Escribe bool.
type: docs
weight: 248
url: /es/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) método


Determina si un audio se rebobina automáticamente al comienzo después de reproducirse. Escribe **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Agregar marco de audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Configurar audio para reproducirse en todas las diapositivas
audioFrame->set_PlayAcrossSlides(true);

// Configurar audio para rebobinar automáticamente al inicio después de reproducirse
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)