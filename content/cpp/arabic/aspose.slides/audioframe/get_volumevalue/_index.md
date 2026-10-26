---
title: get_VolumeValue()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد حجم الصوت كنسبة مئوية. قراءة float.
type: docs
weight: 378
url: /ar/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() طريقة

يعيد حجم الصوت كنسبة مئوية. قراءة **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## ملاحظات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// تعيين مدة التلاشي الابتدائي إلى 200 مللي ثانية
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [AudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)