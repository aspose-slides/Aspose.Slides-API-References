---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าหน้าสไลด์ที่ซ่อนไว้จะถูกส่งออกหรือไม่ ค่าปริยายคือ false.
type: docs
weight: 27
url: /th/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() เมธอด


กำหนดว่าหน้าสไลด์ที่ซ่อนไว้จะถูกส่งออกหรือไม่ ค่าปริยายคือ false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
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