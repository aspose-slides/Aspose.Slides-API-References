---
title: set_ReadOnlyRecommended()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าข้อแนะนำให้เป็นแบบอ่านอย่างเดียว เขียนค่า bool.
type: docs
weight: 92
url: /th/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) วิธีการ


ตั้งค่าการแนะนำให้อ่านอย่างเดียว เขียน **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)