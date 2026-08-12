---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว ISummaryZoomSection.
type: docs
weight: 1
url: /th/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) เมธอด

ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## หมายเหตุ

ตัวอย่างนี้แสดงการดึงองค์ประกอบ Summary Zoom [Section](../../section/) โดยใช้ตำแหน่ง: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)