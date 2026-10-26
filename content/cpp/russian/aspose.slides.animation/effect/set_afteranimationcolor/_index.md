---
title: set_AfterAnimationColor()
second_title: Aspose.Slides для C++ API Reference
description: Определяет цвет после анимации для эффекта. Запишите IColorFormat.
type: docs
weight: 261
url: /ru/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) метод


Определяет цвет после анимации для эффекта. Запишите [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## Примечания



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IColorFormat](../../../aspose.slides/icolorformat/)
* Класс [Effect](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)