---
title: set_AfterAnimationColor()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Definuje barvu po animaci pro efekt. Zapište IColorFormat.
type: docs
weight: 261
url: /cs/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) method

Definuje barvu po animaci pro efekt. Zapište [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získejte první efekt první snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změňte typ po animaci efektu na "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Nastavte barvu po animaci efektu.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IColorFormat](../../../aspose.slides/icolorformat/)
* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)