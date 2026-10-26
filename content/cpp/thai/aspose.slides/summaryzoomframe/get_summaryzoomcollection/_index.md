---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึง ISummaryZoomSectionCollection สำหรับวัตถุ Summary Zoom Frame
type: docs
weight: 14
url: /th/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() เมธอด

รับ [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) สำหรับวัตถุ Summary Zoom Frame

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## หมายเหตุ

ตัวอย่างแสดงการดึงเอาองค์ประกอบ Summary Zoom [Section](../../section/) โดยใช้ดัชนี:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* คลาส [SummaryZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)