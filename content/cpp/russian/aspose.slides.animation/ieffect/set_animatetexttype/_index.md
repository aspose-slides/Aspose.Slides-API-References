---
title: set_AnimateTextType()
second_title: Справочник API Aspose.Slides для C++
description: Определяет тип анимации текста для эффекта. Текст фигуры может быть анимирован по букве, по слову или сразу целиком. Напишите AnimateTextType.
type: docs
weight: 287
url: /ru/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) метод


Определяет тип анимации текста для эффекта. Текст фигуры может быть анимирован по буквам, по словам или сразу полностью. Напишите [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
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

* Перечисление [AnimateTextType](../../animatetexttype/)
* Класс [IEffect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)