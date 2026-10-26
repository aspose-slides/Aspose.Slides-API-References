---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides برای C++ - مرجع API
description: تعیین می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. خواندنی bool.
type: docs
weight: 209
url: /fa/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() متد


تعیین می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا خیر. خواندنی **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// افزودن فریم صوتی
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// تنظیم صدا برای پخش در تمام اسلایدها
audioFrame->set_PlayAcrossSlides(true);

// تنظیم صدا برای بازگرداندن خودکار به ابتدا پس از پخش
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)