---
title: get_FadeInDuration()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يحدد المدة الزمنية للخلط التدريجي الأولي للوسائط بالملي ثانية. قراءة float.
type: docs
weight: 326
url: /ar/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() طريقة


يحدد المدة الزمنية للخلط التدريجي الأولي للوسائط بالملي ثانية. قراءة **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوتي
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [AudioFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)