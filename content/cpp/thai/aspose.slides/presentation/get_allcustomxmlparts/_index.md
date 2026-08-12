---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ส่งคืนส่วนข้อมูลที่กำหนดเองทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว ICustomXmlPart[].
type: docs
weight: 287
url: /th/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() เมธอด

ส่งคืนส่วนข้อมูลที่กำหนดเองทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการลบส่วน xml ที่กำหนดเองทั้งหมดจาก PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ICustomXmlPart](../../icustomxmlpart/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)