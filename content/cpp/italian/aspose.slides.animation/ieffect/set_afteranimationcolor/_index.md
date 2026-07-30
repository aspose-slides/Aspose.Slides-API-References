---
title: set_AfterAnimationColor()
second_title: Riferimento API di Aspose.Slides per C++
description: Definito un colore dopo l'animazione per l'effetto. Scrivi IColorFormat.
type: docs
weight: 261
url: /it/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metodo

Definito un colore dopo l'animazione per l'effetto. Scrivi [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColorFormat](../../../aspose.slides/icolorformat/)
* Classe [IEffect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)