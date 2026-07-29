---
title: get_RewindAudio()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om ljudet automatiskt spolas tillbaka till början efter uppspelning. Läs bool.
type: docs
weight: 235
url: /sv/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() metod

Bestämmer om ljudet automatiskt spolas tillbaka till början efter uppspelning. Läs **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Lägg till ljudram
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Se också

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)