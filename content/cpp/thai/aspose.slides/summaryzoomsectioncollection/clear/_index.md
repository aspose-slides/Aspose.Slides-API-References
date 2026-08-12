---
title: Clear()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบวัตถุ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน.
type: docs
weight: 105
url: /th/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() เมธอด

ลบวัตถุ [SummaryZoomSection](../../summaryzoomsection/) ทั้งหมดออกจากคอลเลกชัน.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## หมายเหตุ

ตัวอย่างแสดงการดึงเอาองค์ประกอบ Summary Zoom [Section](../../section/) โดยใช้ดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## ดูเพิ่มเติม

* คลาส [SummaryZoomSectionCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)