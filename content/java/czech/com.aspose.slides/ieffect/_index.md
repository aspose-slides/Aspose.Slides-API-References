---
title: IEffect
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje animační efekt.
type: docs
url: /cs/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Reprezentuje animační efekt.
## Metody

| Metoda | Popis |
| --- | --- |
| [getSequence()](#getSequence--) | Vrací sekvenci pro efekt. |
| [getTextAnimation()](#getTextAnimation--) | Vrací textovou animaci. |
| [getPresetClassType()](#getPresetClassType--) | Definuje třídu efektu. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definuje třídu efektu. |
| [getType()](#getType--) | Definuje typ efektu. |
| [setType(int value)](#setType-int-) | Definuje typ efektu. |
| [getSubtype()](#getSubtype--) | Definuje podtyp efektu. |
| [setSubtype(int value)](#setSubtype-int-) | Definuje podtyp efektu. |
| [getBehaviors()](#getBehaviors--) | Vrací kolekci chování pro efekt. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Vrací kolekci chování pro efekt. |
| [getTiming()](#getTiming--) | Definuje časovou hodnotu pro efekt. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definuje časovou hodnotu pro efekt. |
| [getTargetShape()](#getTargetShape--) | Vrací cílový tvar pro efekt. |
| [getSound()](#getSound--) | Definuje vložený zvuk pro efekt. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definuje vložený zvuk pro efekt. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Tento atribut určuje, zda animace zastavuje předchozí zvuk. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Tento atribut určuje, zda animace zastavuje předchozí zvuk. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definuje typ po animaci pro efekt. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definuje typ po animaci pro efekt. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definuje barvu po animaci pro efekt. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definuje barvu po animaci pro efekt. |
| [getAnimateTextType()](#getAnimateTextType--) | Definuje typ animovaného textu pro efekt. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definuje typ animovaného textu pro efekt. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definuje zpoždění mezi částmi animovaného textu (slovy nebo písmeny). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definuje zpoždění mezi částmi animovaného textu (slovy nebo písmeny). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Vrací sekvenci pro efekt. Pouze pro čtení [ISequence](../../com.aspose.slides/isequence).

**Vrací:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Vrací textovou animaci. Pouze pro čtení [ITextAnimation](../../com.aspose.slides/itextanimation).

**Vrací:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Definuje třídu efektu. Čtení/zápis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Vrací:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Definuje třídu efektu. Čtení/zápis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Definuje typ efektu. Čtení/zápis [EffectType](../../com.aspose.slides/effecttype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Definuje typ efektu. Čtení/zápis [EffectType](../../com.aspose.slides/effecttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Definuje podtyp efektu. Čtení/zápis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Vrací:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Definuje podtyp efektu. Čtení/zápis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Vrací kolekci chování pro efekt. Čtení/zápis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Vrací:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Vrací kolekci chování pro efekt. Čtení/zápis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Definuje časovou hodnotu pro efekt. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Vrací:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Definuje časovou hodnotu pro efekt. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Vrací cílový tvar pro efekt. Pouze pro čtení [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Definuje vložený zvuk pro efekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá sekvenci efektů pro snímek
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrahuje zvuk efektu do bajtového pole
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Definuje vložený zvuk pro efekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá sekvenci efektů pro snímek
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrahuje zvuk efektu do bajtového pole
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Tento atribut určuje, zda animace zastavuje předchozí zvuk. Čtení/zápis boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Získá první efekt druhého snímku.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Změní druhý efekt Enhancements/Sound na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrací:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


Tento atribut určuje, zda animace zastavuje předchozí zvuk. Čtení/zápis boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Získá první efekt druhého snímku.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Změní druhý efekt Enhancements/Sound na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Definuje typ po animaci pro efekt. Čtení/zápis AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní efekt po animaci na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Definuje typ po animaci pro efekt. Čtení/zápis AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní efekt po animaci na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Definuje barvu po animaci pro efekt. Čtení/zápis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ efektu po animaci na "Color"
> 
>      // Nastaví barvu efektu po animaci.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Definuje barvu po animaci pro efekt. Čtení/zápis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ efektu po animaci na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Nastaví barvu efektu po animaci.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Definuje typ animovaného textu pro efekt. Text tvaru může být animován písmeny, slovy nebo najednou. Čtení/zápis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Definuje typ animovaného textu pro efekt. Text tvaru může být animován písmeny, slovy nebo najednou. Čtení/zápis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Definuje zpoždění mezi částmi animovaného textu (slovy nebo písmeny). Kladná hodnota určuje procento trvání efektu. Záporná hodnota určuje zpoždění v sekundách. Čtení/zápis float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Nastaví zpoždění mezi částmi animovaného textu na 20 % trvání efektu.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Definuje zpoždění mezi částmi animovaného textu (slovy nebo písmeny). Kladná hodnota určuje procento trvání efektu. Záporná hodnota určuje zpoždění v sekundách. Čtení/zápis float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Nastaví zpoždění mezi částmi animovaného textu na 20 % trvání efektu.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |