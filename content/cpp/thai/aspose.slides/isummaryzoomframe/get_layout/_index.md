---
title: get_Layout()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: รับการจัดวางของส่วน Summary Zoom ในเฟรม ค่าเริ่มต้นคือ GridLayout.
type: docs
weight: 1
url: /th/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() เมธอด


รับการจัดวางของส่วน Summary Zoom ในเฟรม ค่าเริ่มต้นคือ GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## หมายเหตุ


ตัวอย่างนี้แสดงการดึงองค์ประกอบ Summary Zoom [Section](../../section/) ตามดัชนี: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## ดูเพิ่มเติม

* Enum [ZoomLayout](../../zoomlayout/)
* คลาส [ISummaryZoomFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)