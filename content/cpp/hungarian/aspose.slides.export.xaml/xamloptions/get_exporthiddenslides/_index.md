---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API hivatkozás
description: Megállapítja, hogy a rejtett diák exportálásra kerülnek-e.
type: docs
weight: 1
url: /hu/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() metódus


Megállapítja, hogy a rejtett diák exportálásra kerülnek-e.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Megjegyzés



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