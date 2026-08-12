---
title: GetSensitivityLabels()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับอาร์เรย์ของ sensitivity labels จาก custom document properties (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /th/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() เมธอด

รับอาร์เรย์ของ sensitivity labels จาก custom document properties (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## หมายเหตุ

โค้ดต่อไปนี้แสดงวิธีย้ายข้อมูล sensitivity labels จาก custom document properties ไปยัง collection ของ SensitivityLabels สมัยใหม่:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// ดึง sensitivity labels จาก custom document properties
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // เพิ่ม label ไปยัง collection
    // ที่นี่คุณสามารถเพิ่มการตรวจสอบความถูกต้องของข้อมูล label (label มีอยู่ เป็นต้น)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISensitivityLabel](../../isensitivitylabel/)
* คลาส [DocumentProperties](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)