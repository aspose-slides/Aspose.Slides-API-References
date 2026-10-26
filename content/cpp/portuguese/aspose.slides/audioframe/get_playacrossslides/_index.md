---
title: get_PlayAcrossSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o áudio está reproduzindo ao longo dos slides. Leitura bool.
type: docs
weight: 209
url: /pt/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() método

Determina se o áudio está reproduzindo ao longo dos slides. Leitura **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Adicionar Quadro de Áudio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Definir áudio para tocar ao longo dos slides
audioFrame->set_PlayAcrossSlides(true);

// Definir áudio para retroceder automaticamente ao início após a reprodução
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Veja Também

* Classe [AudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)