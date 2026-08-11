---
title: get_FadeInDuration()
second_title: Aspose.Slides برای C++ - مرجع API
description: مدت زمان محو شدن اولیهٔ رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی float.
type: docs
weight: 326
url: /fa/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() متد


مدت زمان محو شدن اولیه رسانه را برحسب میلی‌ثانیه مشخص می‌کند. خواندنی **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان محو شدن اولیه برای 200 میلی‌ثانیه
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [IAudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)