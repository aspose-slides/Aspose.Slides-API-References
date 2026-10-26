---
title: set_PlayAcrossSlides()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا نه. مقدار bool را بنویسید.
type: docs
weight: 222
url: /fa/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) متد


تعیین می‌کند که آیا صدا در تمام اسلایدها پخش می‌شود یا نه. مقدار **bool** را بنویسید.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// افزودن قاب صوتی
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// تنظیم صدا برای پخش در تمام اسلایدها
audioFrame->set_PlayAcrossSlides(true);

// تنظیم صدا برای بازگشت خودکار به ابتدا پس از پخش
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## مراجع

* کلاس [AudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)