---
title: get_ExportHiddenSlides()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا اسلایدهای مخفی صادر می‌شوند یا خیر.
type: docs
weight: 1
url: /fa/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() متد


مشخص می‌کند که آیا اسلایدهای مخفی صادر می‌شوند یا خیر.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## موارد مرتبط

* کلاس [IXamlOptions](../)
* فضای‌نام [Aspose::Slides::Export::Xaml](../../)
* کتابخانه [Aspose.Slides](../../../)