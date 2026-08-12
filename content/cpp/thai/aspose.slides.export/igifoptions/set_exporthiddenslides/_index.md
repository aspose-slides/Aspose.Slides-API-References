---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.
type: docs
weight: 40
url: /th/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) เมธอด

กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## ดูเพิ่มเติม

* คลาส [IGifOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)