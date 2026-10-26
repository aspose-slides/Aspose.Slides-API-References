---
title: AddFromHtml()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มข้อความจากสตริง HTML ที่ระบุเข้าสู่คอลเลกชัน.
type: docs
weight: 92
url: /th/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) method

เพิ่มข้อความจากสตริง HTML ที่ระบุเข้าสู่คอลเลกชัน.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความ HTML |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

เพิ่มข้อความจากสตริง HTML ที่ระบุเข้าสู่คอลเลกชัน.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback Resolver ที่ทำการแก้ไข URI และดึงอ็อบเจ็กต์ที่อ้างอิง |
| uri | [System::String](../../../system/string/) | URI สำหรับการเพิ่มเอกสาร HTML. ใช้สำหรับการแก้ไขลิงก์แบบสัมพันธ์ |

## หมายเหตุ

การระบุ resolver อาจทำให้เกิดช่องโหว่ได้. ใช้ด้วยความระมัดระวัง.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)