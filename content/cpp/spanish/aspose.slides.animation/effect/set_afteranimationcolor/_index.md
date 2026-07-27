---
title: set_AfterAnimationColor()
second_title: Referencia de la API de Aspose.Slides para C++
description: Define un color después de la animación para el efecto. Escriba IColorFormat.
type: docs
weight: 261
url: /es/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) método


Define un color después de la animación para el efecto. Escriba [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
```

## Observaciones



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IColorFormat](../../../aspose.slides/icolorformat/)
* Clase [Effect](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)