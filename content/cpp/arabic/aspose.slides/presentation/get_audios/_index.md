---
title: get_Audios()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تُرجِع مجموعة جميع ملفات الصوت المضمنة في العرض التقديمي. للقراءة فقط IAudioCollection.
type: docs
weight: 222
url: /ar/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() طريقة


تُرجِع مجموعة جميع ملفات الصوت المضمنة في العرض التقديمي. للقراءة فقط [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## ملاحظات


توضح الأمثلة التالية كيفية إضافة ارتباط تشعبي إلى ملف صوتي. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAudioCollection](../../iaudiocollection/)
* فئة [Presentation](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)