---
title: get_VolumeValue()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ljudvolymen i procent. Läs float.
type: docs
weight: 378
url: /sv/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() metod

Returnerar ljudvolymen i procent. Läs **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Anmärkningar

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in varaktigheten för startfadet till 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IAudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)