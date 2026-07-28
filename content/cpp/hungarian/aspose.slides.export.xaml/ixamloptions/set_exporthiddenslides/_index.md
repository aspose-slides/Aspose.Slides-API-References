---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API hivatkozás
description: Meghatározza, hogy a rejtett diák exportálásra kerülnek-e.
type: docs
weight: 14
url: /hu/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) metódus


Meghatározza, hogy a rejtett diák exportálásra kerülnek-e.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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
* Névtere [Aspose::Slides::Export::Xaml](../../)
* Könyvtár [Aspose.Slides](../../../)