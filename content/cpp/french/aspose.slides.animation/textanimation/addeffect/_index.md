---
title: AddEffect()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin des animations de texte du groupe. Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d'effets de ce groupe !
type: docs
weight: 53
url: /fr/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) méthode

Ajoute un nouvel effet à la fin de la séquence actuelle jusqu’à la fin des animations de texte du groupe. Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d’effets de ce groupe !

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Type d’un effet d’animation [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sous-types d’effet d’animation [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Type de déclenchement de l’effet [EffectTriggerType](../../effecttriggertype/) |

### Valeur de retour

Nouvel objet d’effet [IEffect](../../ieffect/)

## Voir aussi

* Énumération [EffectType](../../effecttype/)
* Énumération [EffectSubtype](../../effectsubtype/)
* Énumération [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEffect](../../ieffect/)
* Classe [TextAnimation](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)