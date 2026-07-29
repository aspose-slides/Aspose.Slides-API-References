---
title: get_TrimFromStart()
second_title: Aspose.Slides för C++ API-referens
description: Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. Läs float.
type: docs
weight: 404
url: /sv/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() metod

Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. Läser **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in starttrimningstid 1.5 sekunder
audioFrame->set_TrimFromStart(1500.0f);
```

## Se även

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)