---
title: set_VolumeValue()
second_title: Aspose.Slides para C++ Referência da API
description: Define o volume de áudio em porcentagem. Escreva float.
type: docs
weight: 391
url: /pt/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) método

Define o volume de áudio em porcentagem. Escreva **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Define a duração do fade inicial para 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)