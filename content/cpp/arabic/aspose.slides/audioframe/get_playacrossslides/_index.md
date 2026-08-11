---
title: get_PlayAcrossSlides()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كان الصوت يُشغّل عبر الشرائح. قراءة bool.
type: docs
weight: 209
url: /ar/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() طريقة


يحدد ما إذا كان الصوت يُلعب عبر الشرائح. قراءة **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## ملاحظات



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

## انظر أيضًا

* فئة [AudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)