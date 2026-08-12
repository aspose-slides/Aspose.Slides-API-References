---
title: set_PrintComments()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: ระบุว่าจะต้องแสดงความคิดเห็นบนสไลด์หรือไม่
type: docs
weight: 92
url: /th/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) เมธอด


ระบุว่าจะต้องแสดงความคิดเห็นบนสไลด์หรือไม่

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## หมายเหตุ


ค่าเริ่มต้นคือ **false**. 

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## ดูเพิ่มเติม

* คลาส [HandoutLayoutingOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)