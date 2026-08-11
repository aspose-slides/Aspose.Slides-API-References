---
title: set_TrimFromStart()
second_title: Aspose.Slides برای C++ مرجع API
description: مدت زمانی که باید از ابتدای رسانه در حین پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. مقدار float بنویسید.
type: docs
weight: 417
url: /fa/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) متد

مدت زمانی که باید از ابتدای رسانه در حین پخش حذف شود را بر حسب میلی‌ثانیه مشخص می‌کند. **float** بنویسید.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
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