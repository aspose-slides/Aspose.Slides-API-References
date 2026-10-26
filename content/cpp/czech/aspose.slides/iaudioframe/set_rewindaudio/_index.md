---
title: set_RewindAudio()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda se audio automaticky přetočí na začátek po přehrání. Zapište bool.
type: docs
weight: 248
url: /cs/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) metoda


Určuje, zda se audio automaticky přetočí na začátek po přehrání. Zapište **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Přidat zvukový rámeček
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Nastavit audio tak, aby se přehrávalo na všech snímcích
audioFrame->set_PlayAcrossSlides(true);

// Nastavit audio tak, aby se po přehrání automaticky přetočilo na začátek
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)