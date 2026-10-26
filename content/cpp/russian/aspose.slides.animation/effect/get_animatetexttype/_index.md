---
title: get_AnimateTextType()
second_title: Aspose.Slides для C++ справочник API
description: Определяет тип анимации текста для эффекта. Текст формы может быть анимирован по букве, по слову или сразу полностью. Читайте AnimateTextType.
type: docs
weight: 274
url: /ru/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() метод

Определяет тип анимации текста для эффекта. Текст формы может быть анимирован по буквам, по словам или сразу полностью. Читайте [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## Примечания


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## См. также

* Enum [AnimateTextType](../../animatetexttype/)
* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)