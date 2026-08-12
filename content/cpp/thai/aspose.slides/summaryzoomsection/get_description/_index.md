---
title: get_Description()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนข้อความอธิบายของวัตถุ Summary Zoom Section.
type: docs
weight: 27
url: /th/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() เมธอด

ส่งคืนข้อความอธิบายของวัตถุ Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [SummaryZoomSection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)