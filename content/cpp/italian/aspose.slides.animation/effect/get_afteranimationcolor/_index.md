---
title: get_AfterAnimationColor()
second_title: Aspose.Slides per C++ Riferimento API
description: Definisce un colore dopo l'animazione per l'effetto. Leggi IColorFormat.
type: docs
weight: 248
url: /it/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() metodo

Definisce un colore dopo l'animazione per l'effetto. Leggi [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambia il tipo di animazione After dell'effetto a "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Imposta il colore After animation dell'effetto.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColorFormat](../../../aspose.slides/icolorformat/)
* Classe [Effect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)