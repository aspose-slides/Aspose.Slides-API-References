---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om ljudet spelas över bilderna. Skriv bool.
type: docs
weight: 222
url: /sv/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) metod


Bestämmer om ljudet spelas över alla bilder. Skriv **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Lägg till ljudram
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ställ in ljudet så att det spelas över bilderna
audioFrame->set_PlayAcrossSlides(true);

// Ställ in att ljudet automatiskt spolas tillbaka till början efter uppspelning
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Se också

* Klass [AudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)