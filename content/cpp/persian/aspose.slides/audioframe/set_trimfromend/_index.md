---
title: set_TrimFromEnd()
second_title: Aspose.Slides برای مرجع API C++
description: مدت زمان را که باید از انتهای رسانه هنگام پخش حذف شود، بر حسب میلی‌ثانیه مشخص می‌کند. نوشتن float.
type: docs
weight: 443
url: /fa/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) متد

مدت زمان را که باید از انتهای رسانه در هنگام پخش حذف شود، بر حسب میلی‌ثانیه مشخص می‌کند. نوشتن **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the end trimming time 2 seconds
audioFrame->set_TrimFromEnd(2000.0f);
```

## مراجع

* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)