---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides для C++ API справочника
description: Определяет, будут ли скрытые слайды экспортированы.
type: docs
weight: 1
url: /ru/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() метод


Определяет, будут ли скрытые слайды экспортированы.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## См. также

* Класс [IXamlOptions](../)
* Пространство имен [Aspose::Slides::Export::Xaml](../../)
* Библиотека [Aspose.Slides](../../../)