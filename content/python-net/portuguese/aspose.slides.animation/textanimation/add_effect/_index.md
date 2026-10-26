---
title: add_effect method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.animation/textanimation/add_effect/
weight: 20
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Adiciona um novo efeito ao final da sequência atual até o final das animações de texto do grupo.
Only valid if count of text paragraphs equal or greater of counts effect of this group!

### Returns

New effect object [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)

```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) | Tipo de um efeito de animação [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) | Subtipos de efeito de animação [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) | Tipo de acionamento do efeito [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) |

### Veja Também
* enumeration [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype)
* class [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)
* class [`TextAnimation`](/slides/python-net/pt/aspose.slides.animation/textanimation)
* module [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)