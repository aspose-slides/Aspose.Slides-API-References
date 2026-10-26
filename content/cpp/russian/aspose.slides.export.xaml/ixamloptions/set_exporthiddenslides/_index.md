---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, будут ли скрытые слайды экспортированы.
type: docs
weight: 14
url: /ru/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) метод

Определяет, будут ли скрытые слайды экспортированы.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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
* Пространство имён [Aspose::Slides::Export::Xaml](../../)
* Библиотека [Aspose.Slides](../../../)