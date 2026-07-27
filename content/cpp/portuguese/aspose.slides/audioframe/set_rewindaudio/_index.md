---
title: set_RewindAudio()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se o áudio é automaticamente rebobinado para o início após a reprodução. Escreva bool.
type: docs
weight: 248
url: /pt/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) método


Determina se o áudio é automaticamente rebobinado para o início após a reprodução. Escreva **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Adicionar quadro de áudio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Definir áudio para reproduzir em todos os slides
audioFrame->set_PlayAcrossSlides(true);

// Definir áudio para rebobinar automaticamente ao início após a reprodução
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Ver também

* Classe [AudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)