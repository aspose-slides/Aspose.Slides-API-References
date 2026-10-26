---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy a rejtett diák exportálva lesznek-e.
type: docs
weight: 1
url: /hu/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() metódus


Meghatározza, hogy a rejtett diák exportálva lesznek-e.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Lásd még

* Osztály [IXamlOptions](../)
* Névtér [Aspose::Slides::Export::Xaml](../../)
* Könyvtár [Aspose.Slides](../../../)