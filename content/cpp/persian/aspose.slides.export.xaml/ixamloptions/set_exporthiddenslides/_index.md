---
title: set_ExportHiddenSlides()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا خیر.
type: docs
weight: 14
url: /fa/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) متد


تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا خیر.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## موارد مرتبط

* کلاس [IXamlOptions](../)
* فضای نام [Aspose::Slides::Export::Xaml](../../)
* کتابخانه [Aspose.Slides](../../../)