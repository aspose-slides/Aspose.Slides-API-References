---
title: get_VolumeValue()
second_title: مرجع API Aspose.Slides برای C++
description: حجم صدا را به درصد بر می‌گرداند. مقدار را به صورت float می‌خواند.
type: docs
weight: 378
url: /fa/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() متد

حجم صدا را به درصد بر می‌گرداند. **float** خوانده می‌شود.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صدا
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان محو شدن شروع به مدت 200 میلی‌ثانیه
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## ارجاع‌ها

* کلاس [IAudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)