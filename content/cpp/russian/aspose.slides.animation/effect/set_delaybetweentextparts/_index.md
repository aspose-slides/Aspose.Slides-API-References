---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides для C++ справочник API
description: Определяет задержку между анимированными частями текста (словами или буквами). Положительное значение задаёт процент длительности эффекта. Отрицательное значение задаёт задержку в секундах. Запишите float.
type: docs
weight: 313
url: /ru/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) метод


Определяет задержку между анимированными частями текста (словами или буквами). Положительное значение задаёт процент от длительности эффекта. Отрицательное значение задаёт задержку в секундах. Запишите **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
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

* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)