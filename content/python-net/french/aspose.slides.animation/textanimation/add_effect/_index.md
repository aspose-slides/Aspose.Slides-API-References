---
title: add_effect method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.animation/textanimation/add_effect/
weight: 20
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Ajoutez un nouvel effet à la fin de la séquence actuelle jusqu'à la fin des animations de texte du groupe.
            Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d'effets de ce groupe!

### Returns

Nouvel objet d'effet [`IEffect`](/slides/python-net/fr/aspose.slides.animation/ieffect)



```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) | Type d'un effet d'animation [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) | Sous-types d'effet d'animation [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) | Type de déclenchement de l'effet [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) |



### Voir aussi
* énumération [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype)
* énumération [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype)
* énumération [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype)
* classe [`IEffect`](/slides/python-net/fr/aspose.slides.animation/ieffect)
* classe [`TextAnimation`](/slides/python-net/fr/aspose.slides.animation/textanimation)
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)