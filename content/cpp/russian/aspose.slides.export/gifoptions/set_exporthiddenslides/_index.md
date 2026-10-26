---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.
type: docs
weight: 40
url: /ru/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) метод

Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## Замечания

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## См. также

* Класс [GifOptions](../)
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)