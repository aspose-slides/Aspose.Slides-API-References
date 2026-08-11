---
title: get_TrimFromEnd()
second_title: Aspose.Slides برای مرجع API C++
description: مدت زمان را که باید از انتهای رسانه هنگام پخش حذف شود، به میلی‌ثانیه مشخص می‌کند. خواندنی float.
type: docs
weight: 430
url: /fa/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() متد


مدت زمان را که باید از انتهای رسانه هنگام پخش حذف شود، به میلی‌ثانیه مشخص می‌کند. خواندنی **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم زمان برش انتهایی به ۲ ثانیه
audioFrame->set_TrimFromEnd(2000.0f);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)