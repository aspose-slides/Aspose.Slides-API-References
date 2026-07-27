---
title: set_FadeInDuration()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. Escreva float.
type: docs
weight: 339
url: /pt/aspose.slides/iaudioframe/set_fadeinduration/
---
## IAudioFrame::set_FadeInDuration(float) método

Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. Escreva **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeInDuration(float value)=0
```

## Observações

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir a duração do fade inicial para 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [IAudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)