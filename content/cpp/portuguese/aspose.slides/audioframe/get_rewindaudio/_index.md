---
title: get_RewindAudio()
second_title: Referência de API Aspose.Slides para C++
description: Determina se o áudio é automaticamente retrocedido para o início após a reprodução. Leitura bool.
type: docs
weight: 235
url: /pt/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() método

Determina se o áudio é automaticamente retrocedido para o início após a reprodução. Leitura **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Observações

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Adicionar Quadro de Áudio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Definir áudio para reproduzir em todos os slides
audioFrame->set_PlayAcrossSlides(true);

// Definir áudio para retroceder automaticamente ao início após a reprodução
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Veja Também

* Classe [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)