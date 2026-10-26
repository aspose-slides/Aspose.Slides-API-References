---
title: get_RewindAudio()
second_title: Aspose.Slides pro C++ API referenci
description: Určuje, zda je zvuk po přehrání automaticky přetočen na začátek. Čte bool.
type: docs
weight: 235
url: /cs/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() metoda


Určuje, zda je zvuk po přehrání automaticky přetočen na začátek. Čtení **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Poznámky



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)