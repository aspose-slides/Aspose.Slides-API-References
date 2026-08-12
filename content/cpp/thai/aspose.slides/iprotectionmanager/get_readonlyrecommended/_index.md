---
title: get_ReadOnlyRecommended()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับคำแนะนำให้เป็นแบบอ่านอย่างเดียว. อ่าน bool.
type: docs
weight: 79
url: /th/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() เมธอด


รับคำแนะนำให้เป็นแบบอ่านอย่างเดียว. อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IProtectionManager](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)