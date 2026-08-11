---
title: get_FadeOutDuration()
second_title: Aspose.Slides برای مرجع API C++
description: مدت زمان پایان محو شدن رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی float.
type: docs
weight: 352
url: /fa/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() متد

مدت زمان برای محو شدن انتهایی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. قابل خواندن **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان محو شدن انتهایی برای 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)