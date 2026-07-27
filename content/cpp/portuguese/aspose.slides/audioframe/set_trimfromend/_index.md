---
title: set_TrimFromEnd()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a duração de tempo a ser removida do final da mídia durante a reprodução, em milissegundos. Escreva float.
type: docs
weight: 443
url: /pt/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) método

Especifica a duração de tempo a ser removida do final da mídia durante a reprodução, em milissegundos. Escreva **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Observações

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir o tempo de recorte ao final de 2 segundos
audioFrame->set_TrimFromEnd(2000.0f);
```

## Veja Também

* Classe [AudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)