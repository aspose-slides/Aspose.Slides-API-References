---
title: set_RepeatUntilEndSlide()
second_title: Справочник API Aspose.Slides для C++
description: Этот атрибут определяет, будет ли эффект повторяться до конца слайда. Запишите bool.
type: docs
weight: 144
url: /ru/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) метод


Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Запишите **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
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

## Смотрите также

* Класс [ITiming](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)