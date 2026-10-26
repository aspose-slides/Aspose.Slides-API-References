---
title: add_effect method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides.animation/itextanimation/add_effect/
weight: 10
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Añade un nuevo efecto al final de la secuencia actual hasta el final del grupo de animaciones de texto.
Solo es válido si el recuento de párrafos de texto es igual o mayor que el recuento de efectos de este grupo!

### Retorno
Nuevo objeto de efecto [`IEffect`](/slides/python-net/es/aspose.slides.animation/ieffect)

```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) | Tipo de un efecto de animación [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) | Subtipos de efecto de animación [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) | Tipo de activación del efecto [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) |

### Ver también
* enumeración [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype)
* enumeración [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype)
* enumeración [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype)
* clase [`IEffect`](/slides/python-net/es/aspose.slides.animation/ieffect)
* clase [`ITextAnimation`](/slides/python-net/es/aspose.slides.animation/itextanimation)
* módulo [`aspose.slides.animation`](/slides/python-net/es/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)