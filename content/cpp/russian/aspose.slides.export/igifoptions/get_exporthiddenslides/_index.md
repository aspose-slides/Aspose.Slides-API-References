---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, будут ли экспортированы скрытые слайды. Значение по умолчанию — false.
type: docs
weight: 27
url: /ru/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() метод


Определяет, будут ли экспортированы скрытые слайды. Значение по умолчанию — false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## См. также

* Класс [IGifOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)