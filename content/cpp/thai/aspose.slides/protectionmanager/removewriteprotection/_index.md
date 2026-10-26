---
title: RemoveWriteProtection()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ลบการป้องกันการเขียนสำหรับการนำเสนอนี้.
type: docs
weight: 144
url: /th/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() เมธอด


ลบการป้องกันการเขียนของการนำเสนอนี้.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## หมายเหตุ


โค้ดตัวอย่างนี้แสดงวิธีการลบการป้องกันการเขียนจาก PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [ProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)