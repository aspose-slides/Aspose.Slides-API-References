---
title: set_RewindAudio()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدای خود بازگردانده می‌شود. مقدار bool را بنویسید.
type: docs
weight: 248
url: /fa/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) متد


مشخص می‌کند آیا صدا پس از پخش به‌صورت خودکار به ابتدای خود بازگردانده شود. مقدار **bool** را بنویسید.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// افزودن قاب صوتی
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// تنظیم صدا برای پخش در تمام اسلایدها
audioFrame->set_PlayAcrossSlides(true);

// تنظیم صدا برای بازگرداندن خودکار به ابتدای پس از پخش
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)