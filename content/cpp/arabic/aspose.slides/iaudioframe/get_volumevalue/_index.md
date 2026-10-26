---
title: get_VolumeValue()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يرجع حجم الصوت بالنسب المئوية. قراءة float.
type: docs
weight: 378
url: /ar/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() طريقة


يرجع حجم الصوت بالنسب المئوية. قراءة **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// إضافة إطار صوت
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [IAudioFrame](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)