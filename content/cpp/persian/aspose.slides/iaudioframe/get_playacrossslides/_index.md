---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides برای C++ مرجع API
description: تشخیص می‌دهد که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. خواندن bool.
type: docs
weight: 209
url: /fa/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() متد


تعیین می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. خواندن **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// افزودن فریم صوتی
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## همچنین ببینید

* کلاس [IAudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)