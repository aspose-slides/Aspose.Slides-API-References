---
title: AddEffect()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega un nuevo efecto al final de la secuencia actual hasta el final del grupo de animaciones de texto. Solo es válido si la cantidad de párrafos de texto es igual o mayor que la cantidad de efectos de este grupo!
type: docs
weight: 53
url: /es/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) method


Agrega un nuevo efecto al final de la secuencia actual hasta el final del grupo de animaciones de texto. Solo es válido si la cantidad de párrafos de texto es igual o mayor que la cantidad de efectos de este grupo!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Tipo de un efecto de animación [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efecto de animación [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de activación del efecto [EffectTriggerType](../../effecttriggertype/) |

### Valor devuelto

Nuevo objeto de efecto [IEffect](../../ieffect/)

## Ver también

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IEffect](../../ieffect/)
* Clase [ITextAnimation](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)