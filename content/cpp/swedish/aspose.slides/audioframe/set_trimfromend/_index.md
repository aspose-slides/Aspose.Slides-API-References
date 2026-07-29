---
title: set_TrimFromEnd()
second_title: Aspose.Slides för C++ API-referens
description: Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Skriv float.
type: docs
weight: 443
url: /sv/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) metod

Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Skriv **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in trimningstid från slutet 2 sekunder
audioFrame->set_TrimFromEnd(2000.0f);
```

## Se även

* klass [AudioFrame](../)
* namnrymd [Aspose::Slides](../../)
* bibliotek [Aspose.Slides](../../../)