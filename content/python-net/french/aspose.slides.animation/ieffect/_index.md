---
title: IEffect class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.animation/ieffect/
---
## IEffect classe

Représente un effet d'animation.

Le type IEffect expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`sequence`](/slides/python-net/fr/aspose.slides.animation/ieffect/sequence/) | Retourne une séquence pour un effet.<br/> Lecture seule [`ISequence`](/slides/python-net/fr/aspose.slides.animation/isequence). |
| [`text_animation`](/slides/python-net/fr/aspose.slides.animation/ieffect/text_animation/) | Retourne l'animation de texte.<br/> Lecture seule [`ITextAnimation`](/slides/python-net/fr/aspose.slides.animation/itextanimation). |
| [`preset_class_type`](/slides/python-net/fr/aspose.slides.animation/ieffect/preset_class_type/) | Définit la classe de l'effet.<br/> Lecture/écriture [`EffectPresetClassType`](/slides/python-net/fr/aspose.slides.animation/effectpresetclasstype). |
| [`type`](/slides/python-net/fr/aspose.slides.animation/ieffect/type/) | Définit le type de l'effet.<br/> Lecture/écriture [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype). |
| [`subtype`](/slides/python-net/fr/aspose.slides.animation/ieffect/subtype/) | Définit le sous-type de l'effet.<br/> Lecture/écriture [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype). |
| [`behaviors`](/slides/python-net/fr/aspose.slides.animation/ieffect/behaviors/) | Retourne la collection de comportements pour l'effet.<br/> Lecture/écriture [`IBehaviorCollection`](/slides/python-net/fr/aspose.slides.animation/ibehaviorcollection). |
| [`timing`](/slides/python-net/fr/aspose.slides.animation/ieffect/timing/) | Définit la valeur de synchronisation pour l'effet.<br/> Lecture/écriture [`ITiming`](/slides/python-net/fr/aspose.slides.animation/itiming). |
| [`target_shape`](/slides/python-net/fr/aspose.slides.animation/ieffect/target_shape/) | Retourne la forme cible pour l'effet.<br/> Lecture seule [`IShape`](/slides/python-net/fr/aspose.slides/ishape). |
| [`sound`](/slides/python-net/fr/aspose.slides.animation/ieffect/sound/) | Définit le son intégré pour l'effet.<br/> Lecture/écriture [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio). |
| [`stop_previous_sound`](/slides/python-net/fr/aspose.slides.animation/ieffect/stop_previous_sound/) | Cet attribut indique si l'effet d'animation arrête le son précédent.<br/> Lecture/écriture **bool**. |
| [`after_animation_type`](/slides/python-net/fr/aspose.slides.animation/ieffect/after_animation_type/) | Définit un type d'animation après l'effet.<br/> Lecture/écriture [`IEffect.after_animation_type`](/slides/python-net/fr/aspose.slides.animation/ieffect/after_animation_type). |
| [`after_animation_color`](/slides/python-net/fr/aspose.slides.animation/ieffect/after_animation_color/) | Définit une couleur d'animation après l'effet.<br/> Lecture/écriture [`IColorFormat`](/slides/python-net/fr/aspose.slides/icolorformat). |
| [`animate_text_type`](/slides/python-net/fr/aspose.slides.animation/ieffect/animate_text_type/) | Définit un type d'animation de texte pour l'effet.<br/> Le texte de la forme peut être animé lettre par lettre, mot par mot ou tout à la fois.<br/> Lecture/écriture [`IEffect.animate_text_type`](/slides/python-net/fr/aspose.slides.animation/ieffect/animate_text_type). |
| [`delay_between_text_parts`](/slides/python-net/fr/aspose.slides.animation/ieffect/delay_between_text_parts/) | Définit un délai entre les parties de texte animées (mots ou lettres).<br/> Une valeur positive indique le pourcentage de la durée de l'effet.<br/> Une valeur négative indique le délai en secondes.<br/> Lecture/écriture **float**. |


### Voir aussi
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)