---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides для C++ справочник API
description: Определяет задержку между анимированными частями текста (словами или буквами). Положительное значение указывает процент длительности эффекта. Отрицательное значение указывает задержку в секундах. Чтение float.
type: docs
weight: 300
url: /ru/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() метод

Определяет задержку между анимированными частями текста (словами или буквами). Положительное значение указывает процент длительности эффекта. Отрицательное значение указывает задержку в секундах. Чтение **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
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

* Класс [Effect](../)
* Пространство имен [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)