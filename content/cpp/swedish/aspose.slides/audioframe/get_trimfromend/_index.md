---
title: get_TrimFromEnd()
second_title: Aspose.Slides för C++ API-referens
description: Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Läs float.
type: docs
weight: 430
url: /sv/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() metod


Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Läs **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in trimningens sluttid till 2 sekunder
audioFrame->set_TrimFromEnd(2000.0f);
```

## Se också

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)