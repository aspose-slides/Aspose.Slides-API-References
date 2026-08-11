---
title: set_TrimFromStart()
second_title: مرجع API برای Aspose.Slides در C++
description: مدت زمانی را که باید از ابتدای رسانه هنگام پخش حذف شود، بر حسب میلی‌ثانیه مشخص می‌کند. مقدار float.
type: docs
weight: 417
url: /fa/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) متد


مدت زمان را که باید از ابتدای رسانه هنگام پخش حذف شود، بر حسب میلی‌ثانیه مشخص می‌کند. مقدار **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
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

کلاس [IAudioFrame](../)
فضای‌نام [Aspose::Slides](../../)
کتابخانه [Aspose.Slides](../../../)