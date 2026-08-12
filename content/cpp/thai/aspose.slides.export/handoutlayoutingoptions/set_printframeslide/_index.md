---
title: set_PrintFrameSlide()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่
type: docs
weight: 66
url: /th/aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) เมธอด

กำหนดว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
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
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)