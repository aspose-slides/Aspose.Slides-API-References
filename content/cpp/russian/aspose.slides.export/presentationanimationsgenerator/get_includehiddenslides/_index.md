---
title: get_IncludeHiddenSlides()
second_title: Aspose.Slides для C++ справочник API
description: Получает или задаёт, должны ли скрытые слайды быть включены.
type: docs
weight: 27
url: /ru/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const метод


Получает или задаёт, должны ли скрытые слайды быть включены.

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## См. также

* Класс [PresentationAnimationsGenerator](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)