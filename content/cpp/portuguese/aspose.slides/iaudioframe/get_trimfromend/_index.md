---
title: get_TrimFromEnd()
second_title: Referência da API Aspose.Slides para C++
description: Especifica a duração de tempo a ser removida do final da mídia durante a reprodução, em milissegundos. Leitura float.
type: docs
weight: 430
url: /pt/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() método


Especifica a duração de tempo a ser removida do final da mídia durante a reprodução, em milissegundos. Leitura **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar Frame de Áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir o tempo de corte final de 2 segundos
audioFrame->set_TrimFromEnd(2000.0f);
```

## Ver também

* Classe [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)