---
title: set_FadeInDuration()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: يحدد مدة الوقت للفتح التدريجي الأولي للوسائط بالميليثانية. اكتب float.
type: docs
weight: 339
url: /ar/aspose.slides/iaudioframe/set_fadeinduration/
---
## IAudioFrame::set_FadeInDuration(float) طريقة

يحدد مدة الوقت للفتح التدريجي الأولي للوسائط بالميليثانية. اكتب **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeInDuration(float value)=0
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

* الفئة [IAudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)