---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides для C++ справка API
description: Определяет задержку между анимированными частями текста (словами или буквами). Положительное значение указывает процент от длительности эффекта. Отрицательное значение указывает задержку в секундах. Читать float.
type: docs
weight: 300
url: /ru/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() метод


Определяет задержку между анимированными частями текста (слова или буквы). Положительное значение указывает процент от длительности эффекта. Отрицательное значение указывает задержку в секундах. Читать **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
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

## Смотрите также

* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)