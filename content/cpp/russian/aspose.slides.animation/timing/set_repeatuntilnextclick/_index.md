---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides для C++ справочник API
description: Этот атрибут указывает, будет ли эффект повторяться до следующего щелчка. Запишите bool.
type: docs
weight: 170
url: /ru/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) метод


Этот атрибут указывает, будет ли эффект повторяться до следующего щелчка. Запишите **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
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

## Смотрите также

* Класс [Timing](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)