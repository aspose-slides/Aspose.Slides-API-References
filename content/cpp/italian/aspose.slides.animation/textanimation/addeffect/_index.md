---
title: AddEffect()
second_title: Aspose.Slides per C++ Riferimento API
description: Aggiunge un nuovo effetto alla fine della sequenza corrente fino alla fine del gruppo di animazioni di testo. Valido solo se il conteggio dei paragrafi di testo è uguale o maggiore del numero di effetti di questo gruppo!
type: docs
weight: 53
url: /it/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metodo

Aggiunge un nuovo effetto alla fine della sequenza corrente fino alla fine del gruppo di animazioni di testo. Valido solo se il conteggio dei paragrafi di testo è uguale o maggiore del numero di effetti di questo gruppo!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Tipo di un effetto di animazione [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sottotipi di effetto di animazione [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo di attivazione dell'effetto [EffectTriggerType](../../effecttriggertype/) |

### Valore di ritorno

Nuovo oggetto effetto [IEffect](../../ieffect/)

## Vedi anche

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [TextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)