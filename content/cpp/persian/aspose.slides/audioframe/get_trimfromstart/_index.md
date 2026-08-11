---
title: get_TrimFromStart()
second_title: مرجع API Aspose.Slides برای C++
description: مدت زمانی را که باید از ابتدای رسانه هنگام پخش حذف شود، بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن float.
type: docs
weight: 404
url: /fa/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() متد

مدت زمان را که باید از ابتدای رسانه هنگام پخش حذف شود، بر حسب میلی‌ثانیه تعیین می‌کند. قابل خواندن **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)