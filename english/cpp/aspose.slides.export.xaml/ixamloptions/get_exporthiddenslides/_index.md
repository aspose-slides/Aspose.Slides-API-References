---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether hidden slides will be exported.
type: docs
weight: 1
url: /cpp/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() method


Determines whether hidden slides will be exported.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## See Also

* Class [IXamlOptions](../)
* Namespace [Aspose::Slides::Export::Xaml](../../)
* Library [Aspose.Slides](../../../)