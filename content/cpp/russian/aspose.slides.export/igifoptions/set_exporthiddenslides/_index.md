---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.
type: docs
weight: 40
url: /ru/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) метод


Определяет, будут ли скрытые слайды экспортированы. Значение по умолчанию — false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
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