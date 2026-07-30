---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje, zda se audio přehrává napříč snímky. Zapište bool.
type: docs
weight: 222
url: /cs/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) metoda


Určuje, zda se audio přehrává napříč snímky. Zapište **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Přidat audio rámec
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Nastavit audio, aby se přehrávalo napříč snímky
audioFrame->set_PlayAcrossSlides(true);

// Nastavit audio, aby se po přehrání automaticky přetočilo na začátek
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)