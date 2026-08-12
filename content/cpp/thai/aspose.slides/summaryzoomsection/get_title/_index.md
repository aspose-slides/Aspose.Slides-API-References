---
title: get_Title()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนชื่อข้อความของวัตถุ Summary Zoom Section
type: docs
weight: 1
url: /th/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() เมธอด

ส่งคืนชื่อข้อความของวัตถุ Summary Zoom [Section](../../section/) object.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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
* คลาส [SummaryZoomSection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)