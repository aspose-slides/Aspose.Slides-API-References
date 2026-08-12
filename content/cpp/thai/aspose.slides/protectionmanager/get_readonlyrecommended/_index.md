---
title: get_ReadOnlyRecommended()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับคำแนะนำการตั้งค่าแบบอ่านอย่างเดียว. อ่าน bool.
type: docs
weight: 79
url: /th/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() เมธอด


รับคำแนะนำการตั้งค่าแบบอ่านอย่างเดียว. อ่าน **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## หมายเหตุ


ตัวอย่างโค้ดต่อไปนี้แสดงวิธีตั้งค่า PowerPoint [Presentation](../../presentation/) เป็นอ่านอย่างเดียวใน C# โดยใช้ [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [ProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)