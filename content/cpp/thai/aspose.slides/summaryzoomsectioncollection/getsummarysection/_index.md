---
title: GetSummarySection()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนอิลเมนต์ Summary Zoom Section สำหรับส่วนที่กำหนด
type: docs
weight: 92
url: /th/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) เมธอด

ส่งกลับอิลเมนต์ Summary Zoom [Section](../../section/) สำหรับส่วนที่กำหนด.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) เพื่อค้นหา [ISection](../../isection/) |

### ค่าที่ส่งกลับ

[ISummaryZoomSection](../../isummaryzoomsection/) หรือ null หากคอลเลกชันไม่มีอิลเมนต์สำหรับส่วน.

## หมายเหตุ

ตัวอย่างนี้แสดงการดึงอิลเมนต์ Summary Zoom [Section](../../section/) ตามดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomSection](../../isummaryzoomsection/)
* คลาส [ISection](../../isection/)
* คลาส [SummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)