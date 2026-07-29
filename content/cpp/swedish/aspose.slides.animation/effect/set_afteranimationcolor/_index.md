---
title: set_AfterAnimationColor()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en färg efter animation för effekt. Skriv IColorFormat.
type: docs
weight: 261
url: /sv/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) metod

Definierar en färg efter animation för effekt. Skriv [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## Anmärkningar


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra efteranimationstypen för effekten till "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Sätt efteranimationsfärgen för effekten.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IColorFormat](../../../aspose.slides/icolorformat/)
* Klass [Effect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)