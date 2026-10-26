---
title: add_effect method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.animation/itextanimation/add_effect/
weight: 10
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Adiciona um novo efeito ao final da sequência atual até o final das animações de texto do grupo.
Only valid if count of text paragraphs equal or greater of counts effect of this group!

### Retorno

Novo objeto de efeito [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)

```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) |

### Ver também
* enumeração [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype)
* enumeração [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype)
* enumeração [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype)
* classe [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)
* classe [`ITextAnimation`](/slides/python-net/pt/aspose.slides.animation/itextanimation)
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)