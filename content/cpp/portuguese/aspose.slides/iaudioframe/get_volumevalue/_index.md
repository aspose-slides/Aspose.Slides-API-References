---
title: get_VolumeValue()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna o volume de áudio em porcentagem. Somente leitura float.
type: docs
weight: 378
url: /pt/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() método


Retorna o volume de áudio em porcentagem. Somente leitura **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Adicionar quadro de áudio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Ver também

* Classe [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)