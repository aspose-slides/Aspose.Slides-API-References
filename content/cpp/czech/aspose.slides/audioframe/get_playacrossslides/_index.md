---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje, zda se audio přehrává napříč snímky. Čte bool.
type: docs
weight: 209
url: /cs/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() metoda


Určuje, zda se zvuk přehrává napříč snímky. Čte se **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Přidat audio rámec
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Nastavit audio tak, aby se přehrávalo napříč snímky
audioFrame->set_PlayAcrossSlides(true);

// Nastavit audio tak, aby se po přehrání automaticky přetočilo na začátek
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)