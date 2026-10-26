---
title: get_AfterAnimationColor()
second_title: Aspose.Slides för C++ API-referens
description: Definierar en färg efter animation för effekt. Läs IColorFormat.
type: docs
weight: 248
url: /sv/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() metod


Definierar en färg efter animation för effekt. Läs [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
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
* Klass [Effect](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)