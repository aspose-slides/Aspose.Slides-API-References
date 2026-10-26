---
title: ITiming
second_title: Aspose.Slides for Java API Reference
description: Représente le minutage de l'animation.
type: docs
url: /fr/com.aspose.slides/itiming/
---```
public interface ITiming
```

Représente le minutage de l'animation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Describes the percentage of duration accelerate behavior effect. |
| [setAccelerate(float value)](#setAccelerate-float-) | Describes the percentage of duration accelerate behavior effect. |
| [getDecelerate()](#getDecelerate--) | Describes the percentage of duration decelerate behavior effect. |
| [setDecelerate(float value)](#setDecelerate-float-) | Describes the percentage of duration decelerate behavior effect. |
| [getAutoReverse()](#getAutoReverse--) | Describes whether to automatically play the animation in reverse after playing it in the forward direction. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Describes whether to automatically play the animation in reverse after playing it in the forward direction. |
| [getDuration()](#getDuration--) | Describes the duration of animation effect. |
| [setDuration(float value)](#setDuration-float-) | Describes the duration of animation effect. |
| [getRepeatCount()](#getRepeatCount--) | Describes the number of times the effect should repeat. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Describes the number of times the effect should repeat. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | This attribute specifies if the effect will repeat until the end of the slide. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | This attribute specifies if the effect will repeat until the end of the slide. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | This attribute specifies if the effect will repeat until the next click. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | This attribute specifies if the effect will repeat until the next click. |
| [getRepeatDuration()](#getRepeatDuration--) | Describes the number of times the effect should repeat. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Describes the number of times the effect should repeat. |
| [getRestart()](#getRestart--) | Specifies if a effect is to restart after complete. |
| [setRestart(int value)](#setRestart-int-) | Specifies if a effect is to restart after complete. |
| [getSpeed()](#getSpeed--) | Specifies the percentage by which to speed up (or slow down) the timing. |
| [setSpeed(float value)](#setSpeed-float-) | Specifies the percentage by which to speed up (or slow down) the timing. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Describes delay time after trigger. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Describes delay time after trigger. |
| [getTriggerType()](#getTriggerType--) | Describes trigger type. |
| [setTriggerType(int value)](#setTriggerType-int-) | Describes trigger type. |
| [getRewind()](#getRewind--) | This attribute specifies if the effect will rewind when done playing. |
| [setRewind(boolean value)](#setRewind-boolean-) | This attribute specifies if the effect will rewind when done playing. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

Décrit le pourcentage de la durée de l'effet d'accélération du comportement. Lecture/écriture float.

**Renvoie :**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

Décrit le pourcentage de la durée de l'effet d'accélération du comportement. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

Décrit le pourcentage de la durée de l'effet de décélération du comportement. Lecture/écriture float.

**Renvoie :**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

Décrit le pourcentage de la durée de l'effet de décélération du comportement. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

Décrit si l'animation doit être jouée automatiquement en sens inverse après l'avoir jouée dans le sens direct. Lecture/écriture boolean.

**Renvoie :**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

Décrit si l'animation doit être jouée automatiquement en sens inverse après l'avoir jouée dans le sens direct. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

Décrit la durée de l'effet d'animation. Lecture/écriture float.

**Renvoie :**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

Décrit la durée de l'effet d'animation. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

Décrit le nombre de fois que l'effet doit se répéter. Lecture/écriture float.

**Renvoie :**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

Décrit le nombre de fois que l'effet doit se répéter. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

Cet attribut indique si l'effet se répétera jusqu'à la fin de la diapositive. Lecture/écriture boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

Cet attribut indique si l'effet se répétera jusqu'à la fin de la diapositive. Lecture/écriture boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

Cet attribut indique si l'effet se répétera jusqu'au clic suivant. Lecture/écriture boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenez la séquence d'effets pour la première diapositive
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenez le premier effet de la séquence principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Modifiez le minutage/la répétition de l'effet à "Jusqu'au prochain clic"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Renvoie :**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

Cet attribut indique si l'effet se répétera jusqu'au clic suivant. Lecture/écriture boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenez la séquence d'effets pour la première diapositive
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenez le premier effet de la séquence principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Modifiez le minutage/la répétition de l'effet à "Jusqu'au prochain clic"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

Décrit le nombre de fois que l'effet doit se répéter. Lecture/écriture float.

**Renvoie :**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

Décrit le nombre de fois que l'effet doit se répéter. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

Spécifie si un effet doit redémarrer après son achèvement. Lecture/écriture [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Renvoie :**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

Spécifie si un effet doit redémarrer après son achèvement. Lecture/écriture [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

Spécifie le pourcentage d'accélération (ou de décélération) du minutage. Lecture/écriture float.

**Renvoie :**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

Spécifie le pourcentage d'accélération (ou de décélération) du minutage. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

Décrit le temps de retard après le déclencheur. Lecture/écriture float.

**Renvoie :**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

Décrit le temps de retard après le déclencheur. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

Décrit le type de déclencheur. Lecture/écriture [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Renvoie :**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

Décrit le type de déclencheur. Lecture/écriture [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

Cet attribut indique si l'effet sera rembobiné à la fin de sa lecture. Lecture/écriture boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenez la séquence d'effets pour la première diapositive
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenez le premier effet de la séquence principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Activez le minutage/rebobinage de l'effet.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Renvoie :**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

Cet attribut indique si l'effet sera rembobiné à la fin de sa lecture. Lecture/écriture boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenez la séquence d'effets pour la première diapositive
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenez le premier effet de la séquence principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Activez le minutage/rebobinage de l'effet.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |