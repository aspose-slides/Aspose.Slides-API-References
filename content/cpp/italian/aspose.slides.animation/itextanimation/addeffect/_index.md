---
title: AddEffect()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge un nuovo effetto alla fine della sequenza corrente fino alla fine delle animazioni di testo del gruppo. Valido solo se il numero di paragrafi di testo è uguale o maggiore al numero di effetti di questo gruppo!
type: docs
weight: 53
url: /it/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metodo

Aggiungi un nuovo effetto alla fine della sequenza corrente fino alla fine delle animazioni di testo del gruppo. Valido solo se il conteggio dei paragrafi di testo è uguale o maggiore al conteggio degli effetti di questo gruppo!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Tipo di un effetto di animazione [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sottotipi dell'effetto di animazione [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo di trigger dell'effetto [EffectTriggerType](../../effecttriggertype/) |

### Valore di ritorno

Nuovo oggetto effetto [IEffect](../../ieffect/)

## Vedi anche

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [ITextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)