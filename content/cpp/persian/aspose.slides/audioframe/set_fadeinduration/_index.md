---
title: set_FadeInDuration()
second_title: Aspose.Slides برای C++ مرجع API
description: مدت زمان fade-in اولیهٔ رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. مقدار float را بنویسید.
type: docs
weight: 339
url: /fa/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) متد


مدت زمان fade-in اولیهٔ رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. مقدار **float** را بنویسید.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صدا
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان محو‌سازی شروع برای 200 میلی‌ثانیه
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)