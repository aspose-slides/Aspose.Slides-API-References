---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่.
type: docs
weight: 1
url: /th/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() เมธอด


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## ดูเพิ่มเติม

* คลาส [IXamlOptions](../)
* เนมสเปซ [Aspose::Slides::Export::Xaml](../../)
* ไลบรารี [Aspose.Slides](../../../)