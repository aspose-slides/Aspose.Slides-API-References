---
title: set_DelayBetweenTextParts()
second_title: Справочник API Aspose.Slides для C++
description: Определяет задержку между анимированными частями текста (слова или буквы). Положительное значение указывает процент продолжительности эффекта. Отрицательное значение указывает задержку в секундах. Запишите float.
type: docs
weight: 313
url: /ru/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) метод


Определяет задержку между анимированными частями текста (слова или буквы). Положительное значение указывает процент продолжительности эффекта. Отрицательное значение указывает задержку в секундах. Запишите **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## См. также

* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)