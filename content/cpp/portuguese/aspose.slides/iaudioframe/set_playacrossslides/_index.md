---
title: set_PlayAcrossSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se um áudio está sendo reproduzido ao longo dos slides. Escreva bool.
type: docs
weight: 222
url: /pt/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) método


Determina se um áudio está sendo reproduzido ao longo dos slides. Escreva **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Adicionar quadro de áudio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Definir áudio para reproduzir em todos os slides
audioFrame->set_PlayAcrossSlides(true);

// Definir áudio para rebobinar automaticamente ao final da reprodução
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```


## Veja Também

* Classe [IAudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)