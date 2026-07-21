---
title: set_DefaultDelay()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает время задержки по умолчанию [ms].
type: docs
weight: 14
url: /ru/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) метод

Устанавливает время задержки по умолчанию [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
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