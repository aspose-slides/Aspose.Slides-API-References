---
title: get_RewindAudio()
second_title: Referência da API Aspose.Slides para C++
description: Determina se um áudio é rebobinado automaticamente para o início após a reprodução. Leitura bool.
type: docs
weight: 235
url: /pt/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() método


Determina se um áudio é rebobinado automaticamente para o início após a reprodução. Leitura **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Adicionar quadro de áudio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Veja Também

* Classe [IAudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)