---
title: get_AfterAnimationColor()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Definuje barvu po animaci pro efekt. Přečtěte si IColorFormat.
type: docs
weight: 248
url: /cs/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() metoda

Definuje barvu po animaci pro efekt. Přečtěte si [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Poznámky

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Získejte první efekt z první snímku.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Změňte typ After animation na "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Nastavte barvu After animation efektu.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IColorFormat](../../../aspose.slides/icolorformat/)
* Třída [Effect](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Knihovna [Aspose.Slides](../../../)