---
title: set_TrimFromStart()
second_title: Aspose.Slides para Referência da API C++
description: Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Escreva float.
type: docs
weight: 417
url: /pt/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) método


Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Escreva **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir o tempo de corte inicial 1,5 segundos
audioFrame->set_TrimFromStart(1500.0f);
```

## Veja Também

* Classe [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)