---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides pro C++ API reference
description: Určuje, zda se zvuk přehrává napříč snímky. Zapište bool.
type: docs
weight: 222
url: /cs/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) metoda


Určuje, zda se zvuk přehrává napříč snímky. Zapište **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Přidejte zvukový rámec
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Nastavit audio tak, aby se přehrávalo napříč snímky
audioFrame->set_PlayAcrossSlides(true);

// Nastavit audio tak, aby po přehrání automaticky přetočilo na začátek
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)