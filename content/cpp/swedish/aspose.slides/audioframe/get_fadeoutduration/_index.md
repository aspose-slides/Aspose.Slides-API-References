---
title: get_FadeOutDuration()
second_title: Aspose.Slides för C++ API-referens
description: Anger tidslängden för den avslutande tonuttoningen av mediet i millisekunder. Läs float.
type: docs
weight: 352
url: /sv/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() metod

Anger tidslängden för den avslutande tonuttoningen av mediet i millisekunder. Läs **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in varaktigheten för den avslutande tonuttoningen till 500 ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)