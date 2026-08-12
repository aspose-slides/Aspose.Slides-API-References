---
title: Clear()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบวัตถุ SummaryZoomSection ทั้งหมดออกจากคอลเลกชัน.
type: docs
weight: 66
url: /th/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() เมธอด


ลบวัตถุ [SummaryZoomSection](../../summaryzoomsection/) ทั้งหมดออกจากคอลเลกชัน.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## หมายเหตุ


ตัวอย่างแสดงการดึงองค์ประกอบ Summary Zoom [Section](../../section/) ตามดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## ดูเพิ่มเติม

* คลาส [ISummaryZoomSectionCollection](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)