---
title: Effect
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta l'effetto di animazione.
type: docs
url: /it/com.aspose.slides/effect/
---
**Eredita:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Rappresenta l'effetto di animazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSequence()](#getSequence--) | Returns a sequence for an effect. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Read-only [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Defines class of effect. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Defines class of effect. |
| [getType()](#getType--) | Defines type of effect. |
| [setType(int value)](#setType-int-) | Defines type of effect. |
| [getSubtype()](#getSubtype--) | Defines subtype of effect. |
| [setSubtype(int value)](#setSubtype-int-) | Defines subtype of effect. |
| [getBehaviors()](#getBehaviors--) | Returns collection of behavior for effect. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Returns collection of behavior for effect. |
| [getTiming()](#getTiming--) | Defines timing value for effect. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Defines timing value for effect. |
| [getTargetShape()](#getTargetShape--) | Returns target shape for effect. |
| [getSound()](#getSound--) | Defined embedded sound for effect. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Defined embedded sound for effect. |
| [getStopPreviousSound()](#getStopPreviousSound--) | This attribute specifies if the animation effect stops the previous sound. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | This attribute specifies if the animation effect stops the previous sound. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Defines an after animation type for effect. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Defines an after animation type for effect. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Defines an after animation color for effect. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Defines an after animation color for effect. |
| [getAnimateTextType()](#getAnimateTextType--) | Defines an animate text type for effect. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Defines an animate text type for effect. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Defines a delay between animated text parts (words or letters). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Defines a delay between animated text parts (words or letters). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

Restituisce una sequenza per un effetto. Solo lettura [ISequence](../../com.aspose.slides/isequence).

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation Solo lettura [ITextAnimation](../../com.aspose.slides/itextanimation).

**Restituisce:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

Definisce la classe dell'effetto. Lettura/Scrittura [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Restituisce:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

Definisce la classe dell'effetto. Lettura/Scrittura [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Definisce il tipo dell'effetto. Lettura/Scrittura [EffectType](../../com.aspose.slides/effecttype).

**Restituisce:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Definisce il tipo dell'effetto. Lettura/Scrittura [EffectType](../../com.aspose.slides/effecttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

Definisce il sottotipo dell'effetto. Lettura/Scrittura [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Restituisce:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

Definisce il sottotipo dell'effetto. Lettura/Scrittura [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

Restituisce la collezione di comportamenti per l'effetto. Lettura/Scrittura [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Restituisce:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

Restituisce la collezione di comportamenti per l'effetto. Lettura/Scrittura [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Definisce il valore di temporizzazione per l'effetto. Lettura/Scrittura [ITiming](../../com.aspose.slides/itiming).

**Restituisce:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Definisce il valore di temporizzazione per l'effetto. Lettura/Scrittura [ITiming](../../com.aspose.slides/itiming).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

Restituisce la forma target per l'effetto. Solo lettura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Suono incorporato definito per l'effetto. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).
> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Ottiene la sequenza di effetti per la diapositiva
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Estrae il suono dell'effetto in un array di byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Suono incorporato definito per l'effetto. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Ottiene la sequenza di effetti per la diapositiva
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Estrae il suono dell'effetto in un array di byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Lettura/scrittura  boolean .

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ottiene il primo effetto della seconda diapositiva.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Cambia l'effetto secondario Enhancements/Sound in "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Lettura/scrittura  boolean .

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ottiene il primo effetto della seconda diapositiva.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Cambia l'effetto secondario Enhancements/Sound in "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

Definisce un tipo di animazione successiva per l'effetto. Lettura/scrittura [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia l'effetto animazione successiva in "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

Definisce un tipo di animazione successiva per l'effetto. Lettura/scrittura [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia l'effetto animazione successiva in "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

Definisce un colore di animazione successiva per l'effetto. Lettura/scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione successiva dell'effetto in "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Imposta il colore dell'animazione successiva dell'effetto.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

Definisce un colore di animazione successiva per l'effetto. Lettura/scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione successiva dell'effetto in "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Imposta il colore dell'animazione successiva dell'effetto.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Lettura/scrittura  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Lettura/scrittura  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell'effetto. Un valore negativo specifica il ritardo in secondi. Lettura/scrittura  float .

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Imposta il ritardo tra le parti del testo animate al 20% della durata dell'effetto.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell'effetto. Un valore negativo specifica il ritardo in secondi. Lettura/scrittura  float .

---

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Imposta il ritardo tra le parti del testo animate al 20% della durata dell'effetto.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject