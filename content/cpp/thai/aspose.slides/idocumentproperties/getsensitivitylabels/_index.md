---
title: GetSensitivityLabels()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับอาร์เรย์ของป้ายความละเอียดจากคุณสมบัติเข้าเอกสารที่กำหนดเอง (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /th/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() เมธอด

Gets an array of ป้ายความละเอียด from the คุณสมบัติเข้าเอกสารที่กำหนดเอง (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## หมายเหตุ

The following code shows how to move the ป้ายความละเอียด information from the คุณสมบัติเข้าเอกสารที่กำหนดเอง to the modern SensitivityLabels collection: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// รับป้ายความละเอียดจากคุณสมบัติเข้าเอกสารที่กำหนดเอง
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // เพิ่มป้ายลงในคอลเลกชัน
    // ที่นี่คุณสามารถเพิ่มการตรวจสอบความถูกต้องของข้อมูลป้าย (ป้ายพร้อมใช้งาน เป็นต้น)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [IDocumentProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)