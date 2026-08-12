---
title: AddFromHtml()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน
type: docs
weight: 157
url: /th/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) เมธอด

เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความ HTML |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) เมธอด

เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ตัวแก้ไขที่แก้ไข URI และดึงวัตถุที่อ้างอิง |
| uri | [System::String](../../../system/string/) | URI สำหรับเพิ่มเอกสาร HTML ใช้สำหรับแก้ไขลิงก์แบบสัมพันธ์ |

## หมายเหตุ

การระบุ resolver อาจทำให้เกิดช่องโหว่ได้ ใช้อย่างระมัดระวัง

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [ParagraphCollection](../)
* คลาส [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)