---
title: set_VolumeValue()
second_title: Aspose.Slides برای C++ مرجع API
description: حجم صدا را بر حسب درصد تنظیم می‌کند. مقدار float را بنویسید.
type: docs
weight: 391
url: /fa/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) متد


حجم صدا را به درصد تنظیم می‌کند. **float** را بنویسید.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صدا
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان شروع محو شدن به ۲۰۰ میلی‌ثانیه
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## مطالب مرتبط

* کلاس [AudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)