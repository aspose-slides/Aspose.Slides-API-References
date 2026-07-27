---
title: get_InkEffect()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. El valor se analiza a partir de la propiedad del pincel \"inkEffects\". Si no se especifica un efecto reconocido, InkEffectType::NotDefined se devuelve."
type: docs
weight: 53
url: /es/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() método

Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. El valor se analiza a partir de la propiedad del pincel \"inkEffects\". Si no se especifica un efecto reconocido, [InkEffectType::NotDefined](../../inkeffecttype/) se devuelve.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Observaciones

Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Ver también

* Enum [InkEffectType](../../inkeffecttype/)
* Clase [IInkBrush](../)
* Espacio de nombres [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)