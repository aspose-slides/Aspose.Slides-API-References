---
title: get_PlayAcrossSlides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si un audio se reproduce a través de las diapositivas. Lee bool.
type: docs
weight: 209
url: /es/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() método


Determina si un audio se reproduce a través de las diapositivas. Lee **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
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

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)