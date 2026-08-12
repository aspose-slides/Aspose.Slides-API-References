---
title: UpdateDocumentProperties()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อัปเดตคุณสมบัติของการนำเสนอที่เชื่อมต่อ
type: docs
weight: 92
url: /th/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) เมธอด

อัปเดตคุณสมบัติของการนำเสนอที่เชื่อมต่อ.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | คุณสมบัติของเอกสาร [IDocumentProperties](../../idocumentproperties/) |
## หมายเหตุ

ตัวอย่างนี้แสดงวิธีการเรียกเมธอด [IPresentationInfo::UpdateDocumentProperties](./) เพื่ออัปเดตคุณสมบัติของเอกสารที่ได้รับจากการเรียกเมธอด [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/).
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IDocumentProperties](../../idocumentproperties/)
* คลาส [IPresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)