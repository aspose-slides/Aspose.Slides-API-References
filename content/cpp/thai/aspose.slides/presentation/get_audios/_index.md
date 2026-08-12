---
title: get_Audios()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งคืนคอลเลกชันของไฟล์เสียงที่ฝังไว้ทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว IAudioCollection.
type: docs
weight: 222
url: /th/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() เมธอด

ส่งคืนคอลเลกชันของไฟล์เสียงที่ฝังไว้ทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มไฮเปอร์ลิงก์ไปยังไฟล์เสียง. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudioCollection](../../iaudiocollection/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)