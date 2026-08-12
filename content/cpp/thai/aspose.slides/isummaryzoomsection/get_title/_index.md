---
title: get_Title()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ส่งคืนข้อความชื่อของอ็อบเจ็กต์ Summary Zoom Section
type: docs
weight: 1
url: /th/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() เมธอด


ส่งคืนข้อความชื่อของอ็อบเจ็กต์ Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ISummaryZoomSection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)