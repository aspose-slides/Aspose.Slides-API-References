---
title: set_TrimFromEnd()
second_title: Aspose.Slides för C++ API-referens
description: Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Skriv float.
type: docs
weight: 443
url: /sv/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) metod


Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Skriv **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Lägg till ljudram
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ställ in trimning från slutet 2 sekunder
audioFrame->set_TrimFromEnd(2000.0f);
```

## Se även

* Klass [IAudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)