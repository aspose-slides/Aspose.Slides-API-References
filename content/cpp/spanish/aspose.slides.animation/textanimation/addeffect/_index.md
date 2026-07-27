---
title: AddEffect()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega un nuevo efecto al final de la secuencia actual hasta el final del grupo de animaciones de texto. Solo es válido si el número de párrafos de texto es igual o mayor que la cantidad de efectos de este grupo!
type: docs
weight: 53
url: /es/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) método


Agrega un nuevo efecto al final de la secuencia actual hasta el final del grupo de animaciones de texto. ¡Solo es válido si el número de párrafos de texto es igual o mayor que el número de efectos de este grupo!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Tipo de un efecto de animación [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efecto de animación [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de activación del efecto [EffectTriggerType](../../effecttriggertype/) |

### Valor devuelto

Nuevo objeto de efecto [IEffect](../../ieffect/)

## Véase también

* Enumeración [EffectType](../../effecttype/)
* Enumeración [EffectSubtype](../../effectsubtype/)
* Enumeración [EffectTriggerType](../../effecttriggertype/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IEffect](../../ieffect/)
* Clase [TextAnimation](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)