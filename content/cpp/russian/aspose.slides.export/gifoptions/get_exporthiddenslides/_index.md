---
title: get_ExportHiddenSlides()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.
type: docs
weight: 27
url: /ru/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() метод


Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Примечания



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