---
title: get_AfterAnimationColor()
second_title: Aspose.Slides för C++ API-referens
description: Definierade en färg för efteranimation för effekten. Läs IColorFormat.
type: docs
weight: 248
url: /sv/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() metod


Definierade en färg för efteranimation för effekten. Läs [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta den första effekten på den första bilden.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ändra efteranimationstypen för effekten till "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Ställ in efteranimationsfärgen för effekten.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IColorFormat](../../../aspose.slides/icolorformat/)
* Klass [IEffect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)