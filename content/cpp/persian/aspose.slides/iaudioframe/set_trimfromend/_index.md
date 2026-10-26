---
title: set_TrimFromEnd()
second_title: مرجع API Aspose.Slides برای C++
description: مدت زمان قابل حذف از انتهای رسانه هنگام پخش، بر حسب میلی‌ثانیه را مشخص می‌کند. مقدار به صورت float نوشته شود.
type: docs
weight: 443
url: /fa/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) متد

مدت زمان قابل حذف از انتهای رسانه هنگام پخش، بر حسب میلی‌ثانیه را مشخص می‌کند. یک مقدار **float** بنویسید.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن قاب صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم زمان حذف انتها به مدت ۲ ثانیه
audioFrame->set_TrimFromEnd(2000.0f);
```

## موارد مرتبط

* کلاس [IAudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)