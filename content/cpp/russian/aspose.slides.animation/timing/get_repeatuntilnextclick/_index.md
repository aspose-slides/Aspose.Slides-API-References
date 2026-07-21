---
title: get_RepeatUntilNextClick()
second_title: Справочник API Aspose.Slides для C++
description: Этот атрибут указывает, будет ли эффект повторяться до следующего щелчка. Читается bool.
type: docs
weight: 157
url: /ru/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() метод

Этот атрибут указывает, будет ли эффект повторяться до следующего щелчка. Читается **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Примечания

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## См. также

* Класс [Timing](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)