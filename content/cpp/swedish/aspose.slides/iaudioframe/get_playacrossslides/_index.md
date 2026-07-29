---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om ett ljud spelas över bildspelen. Läs bool.
type: docs
weight: 209
url: /sv/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() metod


Avgör om ett ljud spelas över bildspelens bilder. Läs **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Se även

* Klass [IAudioFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)