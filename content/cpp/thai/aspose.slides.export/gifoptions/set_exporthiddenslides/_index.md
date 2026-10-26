---
title: set_ExportHiddenSlides()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ false.
type: docs
weight: 40
url: /th/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) เมธอด

กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
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