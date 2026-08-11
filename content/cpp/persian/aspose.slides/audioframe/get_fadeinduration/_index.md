---
title: get_FadeInDuration()
second_title: مرجع API Aspose.Slides برای C++
description: مدت زمان محو شدن اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی float.
type: docs
weight: 326
url: /fa/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() method


مدت زمان محو شدن اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان محو شدن اولیه به 200 میلی‌ثانیه
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)