---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om ett ljud spelas upp över bildspelen. Skriv bool.
type: docs
weight: 222
url: /sv/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) metod

Bestämmer om ett ljud spelas upp över bildspelen. Skriv **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Anmärkningar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Lägg till ljudram
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ställ in ljudet att spelas över bildspelen
audioFrame->set_PlayAcrossSlides(true);

// Ställ in att ljudet automatiskt spolas tillbaka till början efter uppspelning
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IAudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)