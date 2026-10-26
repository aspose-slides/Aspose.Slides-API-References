---
title: set_ExportHiddenSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le diapositive nascoste verranno esportate.
type: docs
weight: 14
url: /it/aspose.slides.export.xhtml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) metodo


Determina se le diapositive nascoste verranno esportate.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Note



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Vedi anche

* Classe [IXamlOptions](../)
* Spazio dei nomi [Aspose::Slides::Export::Xaml](../../)
* Libreria [Aspose.Slides](../../../)