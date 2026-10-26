---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides برای C++ API مرجع
description: تعیین می‌کند که آیا اسلایدهای مخفی صادر می‌شوند یا خیر.
type: docs
weight: 14
url: /fa/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) متد


تعیین می‌کند که آیا اسلایدهای مخفی صادر می‌شوند یا خیر.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## توضییات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## موارد مرتبط

* کلاس [XamlOptions](../)
* فضای نام [Aspose::Slides::Export::Xaml](../../)
* کتابخانه [Aspose.Slides](../../../)