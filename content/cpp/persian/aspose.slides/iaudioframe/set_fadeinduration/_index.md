---
title: set_FadeInDuration()
second_title: مرجع API Aspose.Slides برای C++
description: مدت زمان محو شدن اولیه رسانه را به میلی‌ثانیه مشخص می‌کند. بنویسید float.
type: docs
weight: 339
url: /fa/aspose.slides/iaudioframe/set_fadeinduration/
---
## IAudioFrame::set_FadeInDuration(float) متد


مدت زمان برای محو شدن اولیه‌ی رسانه به میلی‌ثانیه را مشخص می‌کند. بنویسید **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeInDuration(float value)=0
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
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)