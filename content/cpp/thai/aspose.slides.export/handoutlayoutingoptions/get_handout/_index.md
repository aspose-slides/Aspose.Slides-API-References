---
title: get_Handout()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุจำนวนสไลด์และลำดับที่จะวางบนหน้า HandoutType.
type: docs
weight: 1
url: /th/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const เมธอด

ระบุจำนวนสไลด์และลำดับที่จะวางบนหน้า [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## หมายเหตุ

ค่าปริยายคือ **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## ดูเพิ่มเติม

* Enum [HandoutType](../../handouttype/)
* คลาส [HandoutLayoutingOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)