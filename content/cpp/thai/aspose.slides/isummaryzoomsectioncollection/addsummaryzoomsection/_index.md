---
title: AddSummaryZoomSection()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอ็อบเจกต์ Summary Zoom Section ใหม่และเพิ่มเข้าไปในคอลเลกชัน
type: docs
weight: 14
url: /th/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) วิธีการ


สร้างอ็อบเจกต์ Summary Zoom [Section](../../section/) ใหม่และเพิ่มเข้าไปในคอลเลกชัน

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) สำหรับ Summary Zoom [Section](../../section/) อิลเมนต์ [ISection](../../isection/) |

### ค่าที่คืนกลับ

เพิ่ม [ISummaryZoomFrame](../../isummaryzoomframe/) อิลเมนต์

## หมายเหตุ



หากมีอิลเมนต์สำหรับส่วนนี้อยู่แล้วในคอลเลกชัน, อิลเมนต์ที่มีอยู่จะถูกคืนค่า. 

ตัวอย่างนี้แสดงการดึงอิลเมนต์ Summary Zoom [Section](../../section/) ตามดัชนี: 
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
* คลาส [ISummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)