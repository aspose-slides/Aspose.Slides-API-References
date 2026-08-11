---
title: get_VolumeValue()
second_title: Aspose.Slides برای C++ مرجع API
description: حجم صدا را به درصد برمی‌گرداند. خواندنی float.
type: docs
weight: 378
url: /fa/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() متد


حجم صدا را به درصد برمی‌گرداند. خواندنی **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// افزودن فریم صوتی
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تنظیم مدت زمان محو شدن اولیه برای 200 میلی‌ثانیه
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [AudioFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)