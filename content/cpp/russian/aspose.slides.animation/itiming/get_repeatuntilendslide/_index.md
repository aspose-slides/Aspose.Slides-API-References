---
title: get_RepeatUntilEndSlide()
second_title: Справочник API Aspose.Slides для C++
description: Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читать bool.
type: docs
weight: 131
url: /ru/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() метод


Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читать **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Получает последовательность эффектов для первого слайда
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Получает первый эффект основной последовательности.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Изменяет Timing/Repeat эффекта на "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## См. также

* Класс [ITiming](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)