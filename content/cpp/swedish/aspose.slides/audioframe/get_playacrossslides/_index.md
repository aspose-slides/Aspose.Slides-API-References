---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om ljud spelas upp över bilderna. Läs bool.
type: docs
weight: 209
url: /sv/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() metod

Bestämmer om ljud spelas upp över bilderna. Läs **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Anmärkningar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Lägg till ljudram
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ställ in ljud för uppspelning över bilderna
audioFrame->set_PlayAcrossSlides(true);

// Ställ in att ljudet automatiskt spolas tillbaka till början efter uppspelning
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Se även

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)