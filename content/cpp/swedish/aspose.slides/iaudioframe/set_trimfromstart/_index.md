---
title: set_TrimFromStart()
second_title: Aspose.Slides för C++ API-referens
description: Anger den tidslängd som ska tas bort från början av mediet under uppspelning, i millisekunder. Skriv float.
type: docs
weight: 417
url: /sv/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) metod

Anger den tidslängd som ska tas bort från början av mediet under uppspelning, i millisekunder. Skriv **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Anmärkningar

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in starttrimningstiden 1,5 sekunder
audioFrame->set_TrimFromStart(1500.0f);
```

## Se även

* Klass [IAudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)