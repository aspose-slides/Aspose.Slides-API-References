---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether hidden slides will be exported.
type: docs
weight: 1
url: /aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() method


Determines whether hidden slides will be exported.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## See Also

* Class [XamlOptions](../)
* Namespace [Aspose::Slides::Export::Xaml](../../)
* Library [Aspose.Slides](../../../)