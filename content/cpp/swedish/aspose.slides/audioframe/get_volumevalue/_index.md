---
title: get_VolumeValue()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ljudvolymen i procent. Läs float.
type: docs
weight: 378
url: /sv/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() metod


Returnerar ljudvolymen i procent. Läs **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in varigheten för startfadet till 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)