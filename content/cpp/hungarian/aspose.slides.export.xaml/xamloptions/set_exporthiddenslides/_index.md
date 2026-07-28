---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API-referencia
description: Meghatározza, hogy a rejtett diák exportálásra kerülnek-e.
type: docs
weight: 14
url: /hu/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) metódus

Meghatározza, hogy a rejtett diák exportálásra kerülnek-e.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Lásd még

* Osztály [XamlOptions](../)
* Névtér [Aspose::Slides::Export::Xaml](../../)
* Könyvtár [Aspose.Slides](../../../)