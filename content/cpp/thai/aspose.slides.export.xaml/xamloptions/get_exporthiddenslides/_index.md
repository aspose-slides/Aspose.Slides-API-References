---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าการสไลด์ที่ซ่อนอยู่จะถูกส่งออกหรือไม่.
type: docs
weight: 1
url: /th/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() เมธอด


กำหนดว่าการสไลด์ที่ซ่อนอยู่จะถูกส่งออกหรือไม่.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
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
* Library [Aspose.Slides](../../../)