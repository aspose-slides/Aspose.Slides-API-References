---
title: get_SensitivityLabels()
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: ส่งคืนชุดของป้ายความอ่อนไหวที่ถูกนำไปใช้กับเอกสารงานนำเสนอ. อ่านอย่างเดียว ISensitivityLabelCollection.
type: docs
weight: 378
url: /th/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() วิธีการ

ส่งคืนชุดของป้ายความอ่อนไหวที่ถูกนำไปใช้กับเอกสารงานนำเสนอ อ่านอย่างเดียว [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// พิมพ์ป้ายที่นำไปใช้
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// เพิ่มป้ายใหม่
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// ดึง Id ของป้ายความอ่อนไหวจากนโยบาย
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// ดึงตัวระบุไซต์ Azure AD จากนโยบาย
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)