---
title: AddEffect()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin du groupe d'animations de texte. Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d'effets de ce groupe!
type: docs
weight: 53
url: /fr/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) method


Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin du groupe d'animations de texte. Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d'effets de ce groupe!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Type of an animation effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtypes of animation effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger type of effect [EffectTriggerType](../../effecttriggertype/) |

### Valeur de retour

Nouvel objet d'effet [IEffect](../../ieffect/)

## Voir aussi

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [ITextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)