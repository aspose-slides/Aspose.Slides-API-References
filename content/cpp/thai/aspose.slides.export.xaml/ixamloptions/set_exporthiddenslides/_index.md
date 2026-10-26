---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่
type: docs
weight: 14
url: /th/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) เมธอด


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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