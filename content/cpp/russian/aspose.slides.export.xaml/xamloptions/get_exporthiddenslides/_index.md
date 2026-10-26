---
title: get_ExportHiddenSlides()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, будут ли скрытые слайды экспортированы.
type: docs
weight: 1
url: /ru/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() метод

Определяет, будут ли скрытые слайды экспортированы.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
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