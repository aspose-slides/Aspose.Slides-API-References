---
title: set_PlayAcrossSlides()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si un audio se reproduce a través de las diapositivas. Escribe bool.
type: docs
weight: 222
url: /es/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) método


Determina si un audio se reproduce a través de las diapositivas. Escriba **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Añadir marco de audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Establecer que el audio se reproduzca a través de las diapositivas
audioFrame->set_PlayAcrossSlides(true);

// Establecer que el audio se rebobine automáticamente al inicio después de reproducir
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)