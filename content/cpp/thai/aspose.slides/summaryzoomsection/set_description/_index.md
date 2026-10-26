---
title: set_Description()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งคืนข้อความคำอธิบายของอ็อบเจ็กต์ Summary Zoom Section
type: docs
weight: 40
url: /th/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) เมธอด

ส่งคืนข้อความคำอธิบายของอ็อบเจ็กต์ Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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