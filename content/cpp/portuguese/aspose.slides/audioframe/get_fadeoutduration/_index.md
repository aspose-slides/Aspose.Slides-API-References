---
title: get_FadeOutDuration()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a duração do fade-out final da mídia em milissegundos. Leitura float.
type: docs
weight: 352
url: /pt/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() método


Especifica a duração de tempo para o fade-out final da mídia em milissegundos. Leitura **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir a duração do fade-out final para 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [AudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)