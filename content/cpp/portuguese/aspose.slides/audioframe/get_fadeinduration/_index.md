---
title: get_FadeInDuration()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a duração do fade-in inicial da mídia em milissegundos. Leitura float.
type: docs
weight: 326
url: /pt/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() método

Especifica a duração do fade-in inicial da mídia em milissegundos. Leitura **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar Quadro de Áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir a duração do fade inicial para 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)