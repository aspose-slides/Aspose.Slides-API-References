---
title: IEffect
second_title: Aspose.Slides dla Androida via Java API Reference
description: Reprezentuje efekt animacji.
type: docs
url: /pl/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Reprezentuje efekt animacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSequence()](#getSequence--) | Zwraca sekwencję dla efektu. |
| [getTextAnimation()](#getTextAnimation--) | Zwraca animację tekstu. |
| [getPresetClassType()](#getPresetClassType--) | Definiuje klasę efektu. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definiuje klasę efektu. |
| [getType()](#getType--) | Definiuje typ efektu. |
| [setType(int value)](#setType-int-) | Definiuje typ efektu. |
| [getSubtype()](#getSubtype--) | Definiuje podtyp efektu. |
| [setSubtype(int value)](#setSubtype-int-) | Definiuje podtyp efektu. |
| [getBehaviors()](#getBehaviors--) | Zwraca kolekcję zachowań dla efektu. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Zwraca kolekcję zachowań dla efektu. |
| [getTiming()](#getTiming--) | Definiuje wartość czasu dla efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definiuje wartość czasu dla efektu. |
| [getTargetShape()](#getTargetShape--) | Zwraca docelowy kształt dla efektu. |
| [getSound()](#getSound--) | Zdefiniowano wbudowany dźwięk dla efektu. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Zdefiniowano wbudowany dźwięk dla efektu. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Zdefiniowano typ po animacji dla efektu. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Zdefiniowano typ po animacji dla efektu. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Zdefiniowano kolor po animacji dla efektu. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Zdefiniowano kolor po animacji dla efektu. |
| [getAnimateTextType()](#getAnimateTextType--) | Definiuje typ animowanego tekstu dla efektu. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definiuje typ animowanego tekstu dla efektu. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definiuje opóźnienie między częściami animowanego tekstu (słowa lub litery). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definiuje opóźnienie między częściami animowanego tekstu (słowa lub litery). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Zwraca sekwencję dla efektu. Tylko do odczytu [ISequence](../../com.aspose.slides/isequence).

**Zwraca:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Zwraca animację tekstu. Tylko do odczytu [ITextAnimation](../../com.aspose.slides/itextanimation).

**Zwraca:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Definiuje klasę efektu. Do odczytu i zapisu [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Zwraca:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Definiuje klasę efektu. Do odczytu i zapisu [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Definiuje typ efektu. Do odczytu i zapisu [EffectType](../../com.aspose.slides/effecttype).

**Zwraca:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Definiuje typ efektu. Do odczytu i zapisu [EffectType](../../com.aspose.slides/effecttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Definiuje podtyp efektu. Do odczytu i zapisu [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Zwraca:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Definiuje podtyp efektu. Do odczytu i zapisu [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Zwraca kolekcję zachowań dla efektu. Do odczytu i zapisu [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Zwraca:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Zwraca kolekcję zachowań dla efektu. Do odczytu i zapisu [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Definiuje wartość czasu dla efektu. Do odczytu i zapisu [ITiming](../../com.aspose.slides/itiming).

**Zwraca:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Definiuje wartość czasu dla efektu. Do odczytu i zapisu [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Zwraca docelowy kształt dla efektu. Tylko do odczytu [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Zdefiniowano wbudowany dźwięk dla efektu. Do odczytu i zapisu [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Pobiera sekwencję efektów dla slajdu
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Pobiera dźwięk efektu w postaci tablicy bajtów
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Zdefiniowano wbudowany dźwięk dla efektu. Do odczytu i zapisu [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Pobiera sekwencję efektów dla slajdu
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Pobiera dźwięk efektu w postaci tablicy bajtów
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Do odczytu i zapisu boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Pobierz pierwszy efekt z drugiego slajdu.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Zmień dźwięk drugiego efektu na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Do odczytu i zapisu boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Pobierz pierwszy efekt z drugiego slajdu.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Zmień dźwięk drugiego efektu na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Zdefiniowano typ po animacji dla efektu. Do odczytu i zapisu AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji po efekcie na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Zdefiniowano typ po animacji dla efektu. Do odczytu i zapisu AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień animację po efekcie na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Zdefiniowano kolor po animacji dla efektu. Do odczytu i zapisu [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji po efekcie na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ustaw kolor animacji po efekcie.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Zdefiniowano kolor po animacji dla efektu. Do odczytu i zapisu [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji po efekcie na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ustaw kolor animacji po efekcie.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Definiuje typ animowanego tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub jednocześnie. Do odczytu i zapisu AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animowanego tekstu efektu na "ByLetter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Definiuje typ animowanego tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub jednocześnie. Do odczytu i zapisu AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animowanego tekstu efektu na "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Definiuje opóźnienie między częściami animowanego tekstu (słowa lub litery). Dodatnia wartość określa procent czasu trwania efektu. Ujemna wartość określa opóźnienie w sekundach. Do odczytu i zapisu float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animowanego tekstu efektu na "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Ustaw opóźnienie między częściami animowanego tekstu na 20% czasu trwania efektu.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Definiuje opóźnienie między częściami animowanego tekstu (słowa lub litery). Dodatnia wartość określa procent czasu trwania efektu. Ujemna wartość określa opóźnienie w sekundach. Do odczytu i zapisu float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt z pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animowanego tekstu efektu na "ByWord"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Ustaw opóźnienie między częściami animowanego tekstu na 20% czasu trwania efektu.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |