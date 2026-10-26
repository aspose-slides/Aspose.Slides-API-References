---
title: set_ReadOnlyRecommended()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าข้อแนะนำให้อ่านอย่างเดียว เขียนเป็น bool.
type: docs
weight: 92
url: /th/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) เมธอด

ตั้งค่าข้อแนะนำให้อ่านอย่างเดียว เขียน **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## หมายเหตุ

โค้ดตัวอย่างต่อไปนี้แสดงให้คุณเห็นวิธีการตั้งค่า PowerPoint [Presentation](../../presentation/) เป็นแบบอ่านอย่างเดียวใน C# ด้วยการใช้ [Aspose.Slides](../../).

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [ProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)