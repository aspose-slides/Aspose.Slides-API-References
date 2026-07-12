---
title: ITiming
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation timing.
type: docs
url: /es/com.aspose.slides/itiming/
---```
public interface ITiming
```

Representa la sincronización de animación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Describe el porcentaje de duración del efecto de aceleración del comportamiento. |
| [setAccelerate(float value)](#setAccelerate-float-) | Describe el porcentaje de duración del efecto de aceleración del comportamiento. |
| [getDecelerate()](#getDecelerate--) | Describe el porcentaje de duración del efecto de desaceleración del comportamiento. |
| [setDecelerate(float value)](#setDecelerate-float-) | Describe el porcentaje de duración del efecto de desaceleración del comportamiento. |
| [getAutoReverse()](#getAutoReverse--) | Describe si se reproduce automáticamente la animación en reversa después de reproducirla en dirección hacia adelante. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Describe si se reproduce automáticamente la animación en reversa después de reproducirla en dirección hacia adelante. |
| [getDuration()](#getDuration--) | Describe la duración del efecto de animación. |
| [setDuration(float value)](#setDuration-float-) | Describe la duración del efecto de animación. |
| [getRepeatCount()](#getRepeatCount--) | Describe el número de veces que el efecto debe repetirse. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Describe el número de veces que el efecto debe repetirse. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Este atributo especifica si el efecto se repetirá hasta el siguiente clic. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Este atributo especifica si el efecto se repetirá hasta el siguiente clic. |
| [getRepeatDuration()](#getRepeatDuration--) | Describe el número de veces que el efecto debe repetirse. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Describe el número de veces que el efecto debe repetirse. |
| [getRestart()](#getRestart--) | Especifica si un efecto debe reiniciarse después de completarse. |
| [setRestart(int value)](#setRestart-int-) | Especifica si un efecto debe reiniciarse después de completarse. |
| [getSpeed()](#getSpeed--) | Especifica el porcentaje por el cual acelerar (o ralentizar) el tiempo. |
| [setSpeed(float value)](#setSpeed-float-) | Especifica el porcentaje por el cual acelerar (o ralentizar) el tiempo. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Describe el tiempo de retraso después del desencadenador. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Describe el tiempo de retraso después del desencadenador. |
| [getTriggerType()](#getTriggerType--) | Describe el tipo de desencadenador. |
| [setTriggerType(int value)](#setTriggerType-int-) | Describe el tipo de desencadenador. |
| [getRewind()](#getRewind--) | Este atributo especifica si el efecto rebobinará al terminar de reproducirse. |
| [setRewind(boolean value)](#setRewind-boolean-) | Este atributo especifica si el efecto rebobinará al terminar de reproducirse. |

### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

Describe el porcentaje de duración del efecto de aceleración del comportamiento. Lectura/escritura float.

**Devuelve:**
float

### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

Describe el porcentaje de duración del efecto de aceleración del comportamiento. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

Describe el porcentaje de duración del efecto de desaceleración del comportamiento. Lectura/escritura float.

**Devuelve:**
float

### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

Describe el porcentaje de duración del efecto de desaceleración del comportamiento. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

Describe si se reproduce automáticamente la animación en reversa después de reproducirla en dirección hacia adelante. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

Describe si se reproduce automáticamente la animación en reversa después de reproducirla en dirección hacia adelante. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

Describe la duración del efecto de animación. Lectura/escritura float.

**Devuelve:**
float

### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

Describe la duración del efecto de animación. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

Describe el número de veces que el efecto debe repetirse. Lectura/escritura float.

**Devuelve:**
float

### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

Describe el número de veces que el efecto debe repetirse. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Lectura/escritura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenga la secuencia de efectos para la primera diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenga el primer efecto de la secuencia principal.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Cambie el Timing/Repeat del efecto a "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
boolean

### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Lectura/escritura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenga la secuencia de efectos para la primera diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenga el primer efecto de la secuencia principal.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Cambie el Timing/Repeat del efecto a "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Lectura/escritura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenga la secuencia de efectos para la primera diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenga el primer efecto de la secuencia principal.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Cambie la sincronización/repetición del efecto a "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
boolean

### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Lectura/escritura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenga la secuencia de efectos para la primera diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenga el primer efecto de la secuencia principal.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Cambie el Timing/Repeat del efecto a "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

Describe el número de veces que el efecto debe repetirse. Lectura/escritura float.

**Devuelve:**
float

### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

Describe el número de veces que el efecto debe repetirse. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

Especifica si un efecto debe reiniciarse después de completarse. Lectura/escritura [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Devuelve:**
int

### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

Especifica si un efecto debe reiniciarse después de completarse. Lectura/escritura [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

Especifica el porcentaje por el cual acelerar (o ralentizar) el tiempo. Lectura/escritura float.

**Devuelve:**
float

### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

Especifica el porcentaje por el cual acelerar (o ralentizar) el tiempo. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

Describe el tiempo de retraso después del desencadenador. Lectura/escritura float.

**Devuelve:**
float

### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

Describe el tiempo de retraso después del desencadenador. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

Describe el tipo de desencadenador. Lectura/escritura [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Devuelve:**
int

### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

Describe el tipo de desencadenador. Lectura/escritura [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

Este atributo especifica si el efecto rebobinará al terminar de reproducirse. Lectura/escritura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenga la secuencia de efectos para la primera diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenga el primer efecto de la secuencia principal.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Active la sincronización/Rewind del efecto.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
boolean

### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

Este atributo especifica si el efecto rebobinará al terminar de reproducirse. Lectura/escritura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenga la secuencia de efectos para la primera diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Obtenga el primer efecto de la secuencia principal.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Active la sincronización/Rewind del efecto.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |