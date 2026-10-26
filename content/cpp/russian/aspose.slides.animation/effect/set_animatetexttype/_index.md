---
title: set_AnimateTextType()
second_title: Aspose.Slides для C++ справочник API
description: Определяет тип анимации текста для эффекта. Текст фигуры может быть анимирован по буквам, по словам или сразу целиком. Запишите AnimateTextType.
type: docs
weight: 287
url: /ru/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) метод

Определяет тип анимации текста для эффекта. Текст фигуры может быть анимирован по буквам, по словам или сразу целиком. Запишите [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## Примечания

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить первый эффект первого слайда.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Изменить тип анимации текста эффекта на "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Смотрите также

* Перечисление [AnimateTextType](../../animatetexttype/)
* Класс [Effect](../)
* Пространство имен [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)