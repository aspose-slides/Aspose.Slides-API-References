---
title: get_FadeInDuration()
second_title: Aspose.Slides för C++ API-referens
description: Anger tidslängden för den initiala in-fadingen av mediet i millisekunder. Läs float.
type: docs
weight: 326
url: /sv/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() metod

Anger tidslängden för den initiala in-fadingen av mediet i millisekunder. Läs **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ange varaktigheten för den inledande fade-effekten till 200 ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)