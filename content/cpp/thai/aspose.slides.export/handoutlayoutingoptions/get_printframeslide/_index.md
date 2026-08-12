---
title: get_PrintFrameSlide()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่.
type: docs
weight: 53
url: /th/aspose.slides.export/handoutlayoutingoptions/get_printframeslide/
---
## HandoutLayoutingOptions::get_PrintFrameSlide() const เมธอด


ระบุว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintFrameSlide() const
```

## หมายเหตุ


ค่าเริ่มต้นคือ **true**. 

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## ดูเพิ่มเติม

* คลาส [HandoutLayoutingOptions](../)
* เนมส페ซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)