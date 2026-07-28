---
title: get_AfterAnimationColor()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Definiuje kolor po animacji dla efektu. Zobacz IColorFormat.
type: docs
weight: 248
url: /pl/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() metoda


Definiuje kolor po animacji dla efektu. Zobacz [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Pobierz pierwszy efekt pierwszego slajdu.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Zmień typ po animacji efektu na "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Ustaw kolor po animacji efektu.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IColorFormat](../../../aspose.slides/icolorformat/)
* Klasa [Effect](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)