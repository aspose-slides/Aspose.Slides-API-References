---
title: get_DefaultDelay()
second_title: Aspose.Slides для C++ справка по API
description: Получает время задержки по умолчанию [ms].
type: docs
weight: 1
url: /ru/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const метод


Получает время задержки по умолчанию [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1 с
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## См. также

* Класс [PresentationAnimationsGenerator](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)