---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.
type: docs
weight: 27
url: /th/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() เมธอด

กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## ดูเพิ่มเติม

* คลาส [GifOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)