---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Representa un efecto de animación.
type: docs
url: /es/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Representa un efecto de animación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSequence()](#getSequence--) | Devuelve una secuencia para un efecto. |
| [getTextAnimation()](#getTextAnimation--) | Devuelve animación de texto. |
| [getPresetClassType()](#getPresetClassType--) | Define la clase del efecto. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Define la clase del efecto. |
| [getType()](#getType--) | Define el tipo del efecto. |
| [setType(int value)](#setType-int-) | Define el tipo del efecto. |
| [getSubtype()](#getSubtype--) | Define el subtipo del efecto. |
| [setSubtype(int value)](#setSubtype-int-) | Define el subtipo del efecto. |
| [getBehaviors()](#getBehaviors--) | Devuelve la colección de comportamientos para el efecto. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Devuelve la colección de comportamientos para el efecto. |
| [getTiming()](#getTiming--) | Define el valor de temporización para el efecto. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Define el valor de temporización para el efecto. |
| [getTargetShape()](#getTargetShape--) | Devuelve la forma objetivo del efecto. |
| [getSound()](#getSound--) | Sonido incrustado definido para el efecto. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Sonido incrustado definido para el efecto. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Este atributo especifica si el efecto de animación detiene el sonido anterior. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Este atributo especifica si el efecto de animación detiene el sonido anterior. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definido un tipo de animación posterior para el efecto. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definido un tipo de animación posterior para el efecto. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definido un color de animación posterior para el efecto. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definido un color de animación posterior para el efecto. |
| [getAnimateTextType()](#getAnimateTextType--) | Define un tipo de animación de texto para el efecto. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Define un tipo de animación de texto para el efecto. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Define un retraso entre partes animadas del texto (palabras o letras). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Define un retraso entre partes animadas del texto (palabras o letras). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

Devuelve una secuencia para un efecto. Solo lectura [ISequence](../../com.aspose.slides/isequence).

**Devuelve:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

Devuelve animación de texto. Solo lectura [ITextAnimation](../../com.aspose.slides/itextanimation).

**Devuelve:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

Define la clase del efecto. Lectura/escritura [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Devuelve:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

Define la clase del efecto. Lectura/escritura [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Define el tipo del efecto. Lectura/escritura [EffectType](../../com.aspose.slides/effecttype).

**Devuelve:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Define el tipo del efecto. Lectura/escritura [EffectType](../../com.aspose.slides/effecttype).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

Define el subtipo del efecto. Lectura/escritura [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Devuelve:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

Define el subtipo del efecto. Lectura/escritura [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

Devuelve la colección de comportamientos para el efecto. Lectura/escritura [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Devuelve:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

Devuelve la colección de comportamientos para el efecto. Lectura/escritura [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Define el valor de temporización para el efecto. Lectura/escritura [ITiming](../../com.aspose.slides/itiming).

**Devuelve:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Define el valor de temporización para el efecto. Lectura/escritura [ITiming](../../com.aspose.slides/itiming).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

Devuelve la forma objetivo del efecto. Solo lectura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Sonido incrustado definido para el efecto. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtiene la secuencia de efectos para la diapositiva
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrae el sonido del efecto en un array de bytes
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Sonido incrustado definido para el efecto. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtiene la secuencia de efectos para la diapositiva
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrae el sonido del efecto en un array de bytes
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

Este atributo especifica si el efecto de animación detiene el sonido anterior. Lectura/escritura boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtiene el primer efecto de la segunda diapositiva.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Cambia el sonido del segundo efecto a "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Devuelve:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

Este atributo especifica si el efecto de animación detiene el sonido anterior. Lectura/escritura boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtiene el primer efecto de la segunda diapositiva.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Cambia el sonido del segundo efecto a "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

Definido un tipo de animación posterior para el efecto. Lectura/escritura  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia la animación posterior del efecto a "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Devuelve:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

Definido un tipo de animación posterior para el efecto. Lectura/escritura  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia la animación posterior del efecto a "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

Definido un color de animación posterior para el efecto. Lectura/escritura [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia el tipo de animación posterior del efecto a "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Establece el color de la animación posterior.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

Definido un color de animación posterior para el efecto. Lectura/escritura [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia el tipo de animación posterior del efecto a "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Establece el color de la animación posterior.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

Define un tipo de animación de texto para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Lectura/escritura  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia el tipo de animación de texto del efecto a "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Devuelve:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

Define un tipo de animación de texto para el efecto. El texto de la forma puede animarse por letra, por palabra o todo a la vez. Lectura/escritura  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia el tipo de animación de texto del efecto a "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

Define un retraso entre partes animadas del texto (palabras o letras). Un valor positivo especifica el porcentaje de la duración del efecto. Un valor negativo especifica el retraso en segundos. Lectura/escritura  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia el tipo de animación de texto del efecto a "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Establece el retraso entre partes animadas del texto al 20% de la duración del efecto.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Devuelve:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

Define un retraso entre partes animadas del texto (palabras o letras). Un valor positivo especifica el porcentaje de la duración del efecto. Un valor negativo especifica el retraso en segundos. Lectura/escritura  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtiene el primer efecto de la primera diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia el tipo de animación de texto del efecto a "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Establece el retraso entre partes animadas del texto al 20% de la duración del efecto.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |