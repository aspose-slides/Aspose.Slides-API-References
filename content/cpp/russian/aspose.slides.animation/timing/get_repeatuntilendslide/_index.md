---
title: get_RepeatUntilEndSlide()
second_title: Справочник API Aspose.Slides для C++
description: Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читать bool.
type: docs
weight: 131
url: /ru/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() метод


Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читать **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## См. также

* Класс [Timing](../)
* Пространство имен [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)