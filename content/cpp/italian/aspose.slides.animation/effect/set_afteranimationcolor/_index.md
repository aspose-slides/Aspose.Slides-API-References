---
title: set_AfterAnimationColor()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce un colore dopo l'animazione per l'effetto. Scrivi IColorFormat.
type: docs
weight: 261
url: /it/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metodo


Definisce un colore dopo l'animazione per l'effetto. Scrivi [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Ottieni il primo effetto della prima diapositiva.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Cambia il tipo di animazione After dell'effetto a "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Imposta il colore di animazione After dell'effetto.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColorFormat](../../../aspose.slides/icolorformat/)
* Classe [Effect](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)