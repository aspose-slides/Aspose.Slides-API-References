---
title: get_RewindAudio()
second_title: مرجع Aspose.Slides لواجهة برمجة التطبيقات C++
description: يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة bool.
type: docs
weight: 235
url: /ar/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() طريقة


يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// إضافة إطار صوت
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## انظر أيضًا

* فئة [IAudioFrame](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)