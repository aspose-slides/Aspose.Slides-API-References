---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่.
type: docs
weight: 14
url: /th/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) เมธอด

กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## ดูเพิ่มเติม

* คลาส [XamlOptions](../)
* เนมสเปซ [Aspose::Slides::Export::Xaml](../../)
* ไลบรารี [Aspose.Slides](../../../)