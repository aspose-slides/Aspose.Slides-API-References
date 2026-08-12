---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รับ ISummaryZoomSectionCollection สำหรับอ็อบเจ็กต์ Summary Zoom Frame.
type: docs
weight: 14
url: /th/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() เมธอด

รับ [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) สำหรับอ็อบเจ็กต์ Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## หมายเหตุ

ตัวอย่างนี้สาธิตการดึงองค์ประกอบ Summary Zoom [Section](../../section/) ตามดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* คลาส [ISummaryZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)