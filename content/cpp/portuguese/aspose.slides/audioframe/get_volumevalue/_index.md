---
title: get_VolumeValue()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o volume de áudio em porcentagem. Lê float.
type: docs
weight: 378
url: /pt/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() método


Retorna o volume de áudio em porcentagem. Lê **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Definir a duração do fade inicial para 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Ver também

* Classe [AudioFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)