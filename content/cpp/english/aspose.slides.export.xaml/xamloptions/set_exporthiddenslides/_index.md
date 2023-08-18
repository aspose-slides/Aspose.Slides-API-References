---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether hidden slides will be exported.
type: docs
weight: 14
url: /aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) method


Determines whether hidden slides will be exported.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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