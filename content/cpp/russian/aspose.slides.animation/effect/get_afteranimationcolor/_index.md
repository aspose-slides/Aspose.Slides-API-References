---
title: get_AfterAnimationColor()
second_title: Справочник API Aspose.Slides для C++
description: Определяет цвет после анимации для эффекта. Читайте IColorFormat.
type: docs
weight: 248
url: /ru/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() метод


Определяет цвет после анимации для эффекта. Читайте [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Получить первый эффект первого слайда.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Изменить тип After animation эффекта на "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Установить цвет After animation эффекта.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IColorFormat](../../../aspose.slides/icolorformat/)
* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)