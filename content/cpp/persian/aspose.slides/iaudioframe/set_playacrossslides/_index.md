---
title: set_PlayAcrossSlides()
second_title: مرجع API Aspose.Slides برای C++
description: تشخیص می‌دهد که آیا یک صدا در تمام اسلایدها پخش می‌شود یا خیر. مقدار bool را بنویسید.
type: docs
weight: 222
url: /fa/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) متد


تشخیص می‌دهد که آیا یک صدا در تمام اسلایدها پخش می‌شود یا خیر. مقدار **bool** را بنویسید.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// افزودن فریم صدا
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// تنظیم صدا برای پخش در تمام اسلایدها
audioFrame->set_PlayAcrossSlides(true);

// تنظیم صدا برای بازگرداندن خودکار به ابتدا پس از پخش
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## مراجع

* کلاس [IAudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)