---
title: get_TrimFromStart()
second_title: Aspose.Slides برای C++ مرجع API
description: مدت زمان را که باید از ابتدای رسانه در زمان پخش حذف شود، به میلی‌ثانیه مشخص می‌کند. خواند float.
type: docs
weight: 404
url: /fa/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() متد

مدت زمان را که باید از ابتدای رسانه در زمان پخش حذف شود، به میلی‌ثانیه مشخص می‌کند. خواند **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم زمان برش از ابتدا به 1.5 ثانیه
audioFrame->set_TrimFromStart(1500.0f);
```

## موارد مرتبط

* کلاس [IAudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)