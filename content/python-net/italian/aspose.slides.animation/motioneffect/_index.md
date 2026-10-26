---
title: MotionEffect class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.animation/motioneffect/
---
## MotionEffect classe

Rappresenta il comportamento dell'effetto di movimento dell'effetto.

**Ereditarietà:**[`MotionEffect`](/slides/python-net/it/aspose.slides.animation/motioneffect) → [`Behavior`](/slides/python-net/it/aspose.slides.animation/behavior)

Il tipo MotionEffect espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.animation/motioneffect/__init__/#) | Crea una nuova istanza. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`accumulate`](/slides/python-net/it/aspose.slides.animation/motioneffect/accumulate/) | Rappresenta se i comportamenti dell'animazione sono accumulati.<br/>            Lettura/Scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`additive`](/slides/python-net/it/aspose.slides.animation/motioneffect/additive/) | Rappresenta se il comportamento dell'animazione corrente è combinato con altre animazioni in esecuzione.<br/>            Lettura/Scrittura [`BehaviorAdditiveType`](/slides/python-net/it/aspose.slides.animation/behavioradditivetype). |
| [`properties`](/slides/python-net/it/aspose.slides.animation/motioneffect/properties/) | Rappresenta le proprietà del comportamento.<br/>            Solo lettura [`IBehaviorPropertyCollection`](/slides/python-net/it/aspose.slides.animation/ibehaviorpropertycollection). |
| [`timing`](/slides/python-net/it/aspose.slides.animation/motioneffect/timing/) | Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto.<br/>            Lettura/Scrittura [`ITiming`](/slides/python-net/it/aspose.slides.animation/itiming). |
| [`from_address`](/slides/python-net/it/aspose.slides.animation/motioneffect/from_address/) | Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). <br/>            Lettura/Scrittura [`PointF`](/slides/python-net/it/aspose.slides/pointf). |
| [`to`](/slides/python-net/it/aspose.slides.animation/motioneffect/to/) | Specifica la posizione target per un effetto di movimento dell'animazione (in percentuale).<br/>            Lettura/Scrittura [`PointF`](/slides/python-net/it/aspose.slides/pointf). |
| [`by`](/slides/python-net/it/aspose.slides.animation/motioneffect/by/) | Descrive il valore di offset relativo per l'animazione (in percentuale).<br/>            Lettura/Scrittura [`PointF`](/slides/python-net/it/aspose.slides/pointf). |
| [`rotation_center`](/slides/python-net/it/aspose.slides.animation/motioneffect/rotation_center/) | Descrive il centro di rotazione usato per ruotare un percorso di movimento di un angolo X.<br/>            Lettura/Scrittura [`PointF`](/slides/python-net/it/aspose.slides/pointf). |
| [`origin`](/slides/python-net/it/aspose.slides.animation/motioneffect/origin/) | Specifica a cosa è relativo l'origine del percorso di movimento, ad esempio al layout della diapositiva,<br/>            o al genitore.<br/>            Lettura/Scrittura [`MotionOriginType`](/slides/python-net/it/aspose.slides.animation/motionorigintype). |
| [`path`](/slides/python-net/it/aspose.slides.animation/motioneffect/path/) | Specifica la primitiva del percorso seguita dalle coordinate per il movimento dell'animazione.<br/>            Lettura/Scrittura [`IMotionPath`](/slides/python-net/it/aspose.slides.animation/imotionpath). |
| [`path_edit_mode`](/slides/python-net/it/aspose.slides.animation/motioneffect/path_edit_mode/) | Specifica come il percorso di movimento si sposta quando la forma viene spostata.<br/>            Lettura/Scrittura [`MotionPathEditMode`](/slides/python-net/it/aspose.slides.animation/motionpatheditmode). |
| [`angle`](/slides/python-net/it/aspose.slides.animation/motioneffect/angle/) | Descrive l'angolo relativo del percorso di movimento.<br/>            Lettura/Scrittura **float**. |

### Vedi anche
* classe [`Behavior`](/slides/python-net/it/aspose.slides.animation/behavior)
* classe [`MotionEffect`](/slides/python-net/it/aspose.slides.animation/motioneffect)
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)