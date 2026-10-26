---
title: get_AnimateTextType()
second_title: Aspose.Slides для C++ справочник API
description: Определяет тип анимированного текста для эффекта. Текст фигуры может быть анимирован по букве, по слову или сразу полностью. Читайте AnimateTextType.
type: docs
weight: 274
url: /ru/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() метод

Определяет тип анимированного текста для эффекта. Текст фигуры может быть анимирован по буквам, по словам или сразу полностью. Читайте [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
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
* Класс [IEffect](../)
* Пространство имен [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)