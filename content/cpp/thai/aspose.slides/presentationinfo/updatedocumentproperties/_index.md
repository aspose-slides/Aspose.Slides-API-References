---
title: UpdateDocumentProperties()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อัปเดตคุณสมบัติของการนำเสนอที่เชื่อมต่อ
type: docs
weight: 92
url: /th/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) เมธอด

อัปเดตคุณสมบัติของการนำเสนอที่เชื่อมต่อ

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## หมายเหตุ

ตัวอย่างนี้แสดงวิธีการเรียกเมธอด [PresentationInfo::UpdateDocumentProperties](./) เพื่ออัปเดตคุณสมบัติของเอกสารที่ได้รับจากการเรียกเมธอด [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/)

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDocumentProperties](../../idocumentproperties/)
* คลาส [PresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)