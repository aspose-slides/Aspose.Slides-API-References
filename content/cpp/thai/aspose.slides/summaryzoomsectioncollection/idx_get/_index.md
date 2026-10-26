---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว ISummaryZoomSection.
type: docs
weight: 40
url: /th/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) เมธอด

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## หมายเหตุ

ตัวอย่างแสดงการดึงองค์ประกอบ Summary Zoom [Section](../../section/) ตามดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## ดูเพิ่มเติม

* ประเภทกำหนดใหม่ [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomSection](../../isummaryzoomsection/)
* คลาส [SummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)