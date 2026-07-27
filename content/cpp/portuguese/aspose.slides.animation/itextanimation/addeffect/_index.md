---
title: AddEffect()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um novo efeito ao final da sequência atual até o final das animações de texto em grupo. Válido somente se a contagem de parágrafos de texto for igual ou maior que a contagem de efeitos deste grupo!
type: docs
weight: 53
url: /pt/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) method

Adiciona um novo efeito ao final da sequência atual até o final das animações de texto em grupo. Válido somente se a contagem de parágrafos de texto for igual ou maior que a contagem de efeitos deste grupo!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos do efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de disparo do efeito [EffectTriggerType](../../effecttriggertype/) |

### Valor de Retorno

Novo objeto de efeito [IEffect](../../ieffect/)

## Veja Também

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEffect](../../ieffect/)
* Classe [ITextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)