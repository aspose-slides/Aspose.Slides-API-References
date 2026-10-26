---
title: get_ExportHiddenSlides()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا اسلایدهای مخفی صادر خواهند شد یا نه.
type: docs
weight: 1
url: /fa/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() متد


مشخص می‌کند که آیا اسلایدهای مخفی صادر خواهند شد یا نه.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## موارد مرتبط

* کلاس [XamlOptions](../)
* فضای‌نام [Aspose::Slides::Export::Xaml](../../)
* کتابخانه [Aspose.Slides](../../../)