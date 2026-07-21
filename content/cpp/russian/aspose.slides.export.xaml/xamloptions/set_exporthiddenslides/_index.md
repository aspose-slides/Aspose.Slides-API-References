---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides для C++ справка API
description: Определяет, экспортируются ли скрытые слайды.
type: docs
weight: 14
url: /ru/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) метод


Определяет, экспортируются ли скрытые слайды.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## См. также

* Класс [XamlOptions](../)
* Пространство имён [Aspose::Slides::Export::Xaml](../../)
* Библиотека [Aspose.Slides](../../../)