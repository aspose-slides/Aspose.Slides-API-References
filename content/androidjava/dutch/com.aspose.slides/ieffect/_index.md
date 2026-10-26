---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation effect.
type: docs
url: /nl/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Stelt een animatie-effect voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSequence()](#getSequence--) | Retourneert een reeks voor een effect. |
| [getTextAnimation()](#getTextAnimation--) | Retourneert tekstanimatie. |
| [getPresetClassType()](#getPresetClassType--) | Definieert klasse van effect. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definieert klasse van effect. |
| [getType()](#getType--) | Definieert type van effect. |
| [setType(int value)](#setType-int-) | Definieert type van effect. |
| [getSubtype()](#getSubtype--) | Definieert subtype van effect. |
| [setSubtype(int value)](#setSubtype-int-) | Definieert subtype van effect. |
| [getBehaviors()](#getBehaviors--) | Retourneert een collectie van gedrag voor effect. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Retourneert een collectie van gedrag voor effect. |
| [getTiming()](#getTiming--) | Definieert timingwaarde voor effect. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definieert timingwaarde voor effect. |
| [getTargetShape()](#getTargetShape--) | Retourneert doelvorm voor effect. |
| [getSound()](#getSound--) | Gedefinieerd ingesloten geluid voor effect. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Gedefinieerd ingesloten geluid voor effect. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definieerde een after animatietype voor effect. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definieerde een after animatietype voor effect. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definieerde een after animatiekleur voor effect. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definieerde een after animatiekleur voor effect. |
| [getAnimateTextType()](#getAnimateTextType--) | Definieert een animerende teksttype voor effect. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definieert een animerende teksttype voor effect. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definieert een vertraging tussen geanimeerde tekstonderdelen (woorden of letters). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definieert een vertraging tussen geanimeerde tekstonderdelen (woorden of letters). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Retourneert een reeks voor een effect. Alleen-lezen [ISequence](../../com.aspose.slides/isequence).

**Retourneert:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Retourneert tekstanimatie. Alleen-lezen [ITextAnimation](../../com.aspose.slides/itextanimation).

**Retourneert:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Definieert klasse van effect. Lezen/schrijven [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Retourneert:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Definieert klasse van effect. Lezen/schrijven [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Definieert type van effect. Lezen/schrijven [EffectType](../../com.aspose.slides/effecttype).

**Retourneert:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Definieert type van effect. Lezen/schrijven [EffectType](../../com.aspose.slides/effecttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Definieert subtype van effect. Lezen/schrijven [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Retourneert:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Definieert subtype van effect. Lezen/schrijven [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Retourneert een collectie van gedrag voor effect. Lezen/schrijven [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Retourneert:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Retourneert een collectie van gedrag voor effect. Lezen/schrijven [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Definieert timingwaarde voor effect. Lezen/schrijven [ITiming](../../com.aspose.slides/itiming).

**Retourneert:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Definieert timingwaarde voor effect. Lezen/schrijven [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Retourneert doelvorm voor effect. Alleen-lezen [IShape](../../com.aspose.slides/ishape).

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Gedefinieerd ingesloten geluid voor effect. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haalt de effectensequentie voor de dia op
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Haalt het effectgeluid op als byte-array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Gedefinieerd ingesloten geluid voor effect. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haalt de effectensequentie voor de dia op
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Haalt het effectgeluid op als byte-array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. Lezen/schrijven boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Haal het eerste effect van de tweede dia op.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Wijzig het tweede effect Enhancements/Sound naar "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. Lezen/schrijven boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Haal het eerste effect van de tweede dia op.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Verander het tweede effect Enhancements/Sound naar "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Definieerde een after animatietype voor effect. Lezen/schrijven AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verander het effect After animation naar "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Definieerde een after animatietype voor effect. Lezen/schrijven AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verander het effect After animation naar "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Definieerde een after animatiekleur voor effect. Lezen/schrijven [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verander het effect After animation type naar "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Stel de After animation kleur van het effect in.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Definieerde een after animatiekleur voor effect. Lezen/schrijven [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verander het effect After animation type naar "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Stel de After animation kleur van het effect in.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Definieert een animerende teksttype voor effect. De vormtekst kan worden geanimeerd per letter, per woord of in één keer. Lezen/schrijven AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verander het effect Animate text type naar "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Definieert een animerende teksttype voor effect. De vormtekst kan worden geanimeerd per letter, per woord of in één keer. Lezen/schrijven AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verander het effect Animate text type naar "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Definieert een vertraging tussen geanimeerde tekstonderdelen (woorden of letters). Een positieve waarde geeft het percentage van de effectduur aan. Een negatieve waarde geeft de vertraging in seconden aan. Lezen/schrijven float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Haalt het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verandert het effect Animate text type naar "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Stelt de vertraging tussen geanimeerde tekstonderdelen in op 20% van de effectduur.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Definieert een vertraging tussen geanimeerde tekstonderdelen (woorden of letters). Een positieve waarde geeft het percentage van de effectduur aan. Een negatieve waarde geeft de vertraging in seconden aan. Lezen/schrijven float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Haal het eerste effect van de eerste dia op.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Verander het effect Animate text type naar "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Stel de vertraging tussen geanimeerde tekstonderdelen in op 20% van de effectduur.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |