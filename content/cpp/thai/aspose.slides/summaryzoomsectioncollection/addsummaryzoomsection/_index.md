---
title: AddSummaryZoomSection()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างอ็อบเจ็กต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน
type: docs
weight: 53
url: /th/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) เมธอด

สร้างอ็อบเจ็กต์ Summary Zoom [Section](../../section/) ใหม่และเพิ่มเข้าไปในคอลเลกชัน

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) สำหรับองค์ประกอบ Summary Zoom [Section](../../section/) ใหม่ [ISection](../../isection/) |

### ค่าที่ส่งกลับ

เพิ่ม [ISummaryZoomFrame](../../isummaryzoomframe/) องค์ประกอบ

## หมายเหตุ

หากมีองค์ประกอบสำหรับส่วนนี้อยู่แล้วในคอลเลกชัน, จะส่งคืนองค์ประกอบที่มีอยู่. 

ตัวอย่างนี้แสดงวิธีการดึงองค์ประกอบ Summary Zoom [Section](../../section/) ตามดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomSection](../../isummaryzoomsection/)
* คลาส [ISection](../../isection/)
* คลาส [SummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)