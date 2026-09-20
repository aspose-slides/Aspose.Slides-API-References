---
title: IEffect class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.animation/ieffect/
---
## IEffect classe

Rappresenta l'effetto di animazione.

Il tipo IEffect espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`sequence`](/slides/python-net/it/aspose.slides.animation/ieffect/sequence/) | Restituisce una sequenza per un effetto.<br/>            Sola lettura [`ISequence`](/slides/python-net/it/aspose.slides.animation/isequence). |
| [`text_animation`](/slides/python-net/it/aspose.slides.animation/ieffect/text_animation/) | Restituisce l'animazione del testo.<br/>            Sola lettura [`ITextAnimation`](/slides/python-net/it/aspose.slides.animation/itextanimation). |
| [`preset_class_type`](/slides/python-net/it/aspose.slides.animation/ieffect/preset_class_type/) | Definisce la classe dell'effetto.<br/>            Lettura/scrittura [`EffectPresetClassType`](/slides/python-net/it/aspose.slides.animation/effectpresetclasstype). |
| [`type`](/slides/python-net/it/aspose.slides.animation/ieffect/type/) | Definisce il tipo dell'effetto.<br/>            Lettura/scrittura [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype). |
| [`subtype`](/slides/python-net/it/aspose.slides.animation/ieffect/subtype/) | Definisce il sottotipo dell'effetto.<br/>            Lettura/scrittura [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype). |
| [`behaviors`](/slides/python-net/it/aspose.slides.animation/ieffect/behaviors/) | Restituisce la collezione di comportamenti per l'effetto.<br/>            Lettura/scrittura [`IBehaviorCollection`](/slides/python-net/it/aspose.slides.animation/ibehaviorcollection). |
| [`timing`](/slides/python-net/it/aspose.slides.animation/ieffect/timing/) | Definisce il valore di temporizzazione per l'effetto.<br/>            Lettura/scrittura [`ITiming`](/slides/python-net/it/aspose.slides.animation/itiming). |
| [`target_shape`](/slides/python-net/it/aspose.slides.animation/ieffect/target_shape/) | Restituisce la forma di destinazione per l'effetto.<br/>            Sola lettura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |
| [`sound`](/slides/python-net/it/aspose.slides.animation/ieffect/sound/) | Definisce il suono incorporato per l'effetto.<br/>            Lettura/scrittura [`IAudio`](/slides/python-net/it/aspose.slides/iaudio). |
| [`stop_previous_sound`](/slides/python-net/it/aspose.slides.animation/ieffect/stop_previous_sound/) | Questo attributo specifica se l'effetto di animazione interrompe il suono precedente.<br/>            Lettura/scrittura **bool**. |
| [`after_animation_type`](/slides/python-net/it/aspose.slides.animation/ieffect/after_animation_type/) | Definisce un tipo di animazione successiva per l'effetto.<br/>            Lettura/scrittura [`IEffect.after_animation_type`](/slides/python-net/it/aspose.slides.animation/ieffect/after_animation_type). |
| [`after_animation_color`](/slides/python-net/it/aspose.slides.animation/ieffect/after_animation_color/) | Definisce un colore di animazione successiva per l'effetto.<br/>            Lettura/scrittura [`IColorFormat`](/slides/python-net/it/aspose.slides/icolorformat). |
| [`animate_text_type`](/slides/python-net/it/aspose.slides.animation/ieffect/animate_text_type/) | Definisce un tipo di animazione del testo per l'effetto. <br/>            Il testo della forma può essere animato per lettera, per parola o tutto in una volta.<br/>            Lettura/scrittura [`IEffect.animate_text_type`](/slides/python-net/it/aspose.slides.animation/ieffect/animate_text_type). |
| [`delay_between_text_parts`](/slides/python-net/it/aspose.slides.animation/ieffect/delay_between_text_parts/) | Definisce un ritardo tra le parti di testo animate (parole o lettere).<br/>            Un valore positivo specifica la percentuale della durata dell'effetto.<br/>            Un valore negativo specifica il ritardo in secondi.<br/>            Lettura/scrittura **float**. |

### Vedi anche
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)