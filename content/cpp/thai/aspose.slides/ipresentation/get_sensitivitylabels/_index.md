---
title: get_SensitivityLabels()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนคอลเลกชันของป้ายความสำคัญที่ใช้กับเอกสารงานนำเสนอ. อ่านอย่างเดียว ISensitivityLabelCollection.
type: docs
weight: 391
url: /th/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() เมธอด

ส่งคืนคอลเลกชันของป้ายความสำคัญที่ใช้กับเอกสารงานนำเสนอ. อ่านอย่างเดียว [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// พิมพ์ป้ายที่ถูกนำไปใช้
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// เพิ่มป้ายใหม่
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// รับ Id ของป้ายความสำคัญจากนโยบาย
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// รับตัวระบุไซต์ Azure AD จากนโยบาย
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* คลาส [IPresentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)