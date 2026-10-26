---
title: get_TrimFromStart()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Leia float.
type: docs
weight: 404
url: /pt/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() método


Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Leia **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir o tempo de corte inicial de 1,5 segundos
audioFrame->set_TrimFromStart(1500.0f);
```

## Veja Também

* Classe [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)