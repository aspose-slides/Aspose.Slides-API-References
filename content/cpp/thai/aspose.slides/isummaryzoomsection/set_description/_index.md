---
title: set_Description()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนคำอธิบายข้อความของอ็อบเจกต์ Summary Zoom Section
type: docs
weight: 40
url: /th/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) เมธอด

ส่งคืนคำอธิบายข้อความของวัตถุ Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
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
* คลาส [ISummaryZoomSection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)