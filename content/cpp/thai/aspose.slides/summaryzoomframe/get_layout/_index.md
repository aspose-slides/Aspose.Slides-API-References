---
title: get_Layout()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับการจัดวางของ Summary Zoom Sections ในเฟรม ค่าเริ่มต้นคือ GridLayout.
type: docs
weight: 1
url: /th/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() เมธอด


รับการจัดวางของ Summary Zoom Sections ในเฟรม ค่าเริ่มต้นคือ GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## หมายเหตุ


ตัวอย่างแสดงการดึง Summary Zoom [Section](../../section/) อิลิเมนต์ตามดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## ดูเพิ่มเติม

* Enum [ZoomLayout](../../zoomlayout/)
* คลาส [SummaryZoomFrame](../)
* เนมสเปส [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)