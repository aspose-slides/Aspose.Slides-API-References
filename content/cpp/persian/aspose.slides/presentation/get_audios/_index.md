---
title: get_Audios()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از تمام فایل‌های صوتی جاسازی‌شده در ارائه را برمی‌گرداند. فقط خواندنی IAudioCollection.
type: docs
weight: 222
url: /fa/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() متد

کلکسیون تمام فایل‌های صوتی جاسازی‌شده در ارائه را بازمی‌گرداند. فقط خواندنی [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## توضیحات

مثال‌های زیر نشان می‌دهند که چگونه یک لینک به یک فایل صوتی اضافه شود. ```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudioCollection](../../iaudiocollection/)
* کلاس [Presentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)