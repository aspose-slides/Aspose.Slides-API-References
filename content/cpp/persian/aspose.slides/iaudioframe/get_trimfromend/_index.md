---
title: get_TrimFromEnd()
second_title: مرجع API Aspose.Slides برای C++
description: مدت زمان را که باید در حین پخش از انتهای رسانه حذف شود، بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی float.
type: docs
weight: 430
url: /fa/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() متد

مدت زمان را که باید در حین پخش از انتهای رسانه حذف شود، بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم زمان برش انتها به 2 ثانیه
audioFrame->set_TrimFromEnd(2000.0f);
```

## موارد مرتبط

* کلاس [IAudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)