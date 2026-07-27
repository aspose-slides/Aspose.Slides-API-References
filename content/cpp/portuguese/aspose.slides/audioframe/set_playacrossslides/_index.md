---
title: set_PlayAcrossSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o áudio está sendo reproduzido ao longo dos slides. Escreva bool.
type: docs
weight: 222
url: /pt/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) método


Determina se o áudio está sendo reproduzido ao longo dos slides. Escreva **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Adicionar quadro de áudio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Definir áudio para reproduzir ao longo dos slides
audioFrame->set_PlayAcrossSlides(true);

// Definir áudio para retroceder automaticamente ao início após a reprodução
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Ver Também

* Classe [AudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)