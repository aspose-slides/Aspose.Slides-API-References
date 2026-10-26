---
title: get_AfterAnimationColor()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Definuje barvu po animaci pro efekt. Přečtěte si IColorFormat.
type: docs
weight: 248
url: /cs/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() metoda

Definuje barvu po animaci pro efekt. Přečtěte si [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## Poznámky

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získá první efekt první snímky.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změní typ po animaci efektu na "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Nastaví barvu po animaci efektu.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IColorFormat](../../../aspose.slides/icolorformat/)
* Třída [IEffect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)