---
title: set_FadeOutDuration()
second_title: مرجع API Aspose.Slides برای C++
description: مدت زمان پایان fade-out رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. مقدار float.
type: docs
weight: 365
url: /fa/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) متد


مدت زمان پایان fade-out رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. نوع **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان fade-out انتهایی به 500 میلی‌ثانیه
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## همچنین ببینید

* کلاس [AudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)