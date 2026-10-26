---
title: IEffect
second_title: Aspose.Slides for Java API Reference
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
| [getPresetClassType()](#getPresetClassType--) | Określa klasę efektu. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Określa klasę efektu. |
| [getType()](#getType--) | Określa typ efektu. |
| [setType(int value)](#setType-int-) | Określa typ efektu. |
| [getSubtype()](#getSubtype--) | Określa podtyp efektu. |
| [setSubtype(int value)](#setSubtype-int-) | Określa podtyp efektu. |
| [getBehaviors()](#getBehaviors--) | Zwraca kolekcję zachowań dla efektu. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Zwraca kolekcję zachowań dla efektu. |
| [getTiming()](#getTiming--) | Określa wartość czasu dla efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Określa wartość czasu dla efektu. |
| [getTargetShape()](#getTargetShape--) | Zwraca docelowy kształt dla efektu. |
| [getSound()](#getSound--) | Zdefiniowano wbudowany dźwięk dla efektu. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Zdefiniowano wbudowany dźwięk dla efektu. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Zdefiniowano typ poanimacji dla efektu. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Zdefiniowano typ poanimacji dla efektu. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Zdefiniowano kolor po animacji dla efektu. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Zdefiniowano kolor po animacji dla efektu. |
| [getAnimateTextType()](#getAnimateTextType--) | Określa typ animacji tekstu dla efektu. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Określa typ animacji tekstu dla efektu. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Określa opóźnienie między częściami animowanego tekstu (słowami lub literami). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Określa opóźnienie między częściami animowanego tekstu (słowami lub literami). |
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

Określa klasę efektu. Odczyt/zapis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Zwraca:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

Określa klasę efektu. Odczyt/zapis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Określa typ efektu. Odczyt/zapis [EffectType](../../com.aspose.slides/effecttype).

**Zwraca:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Określa typ efektu. Odczyt/zapis [EffectType](../../com.aspose.slides/effecttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

Określa podtyp efektu. Odczyt/zapis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Zwraca:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

Określa podtyp efektu. Odczyt/zapis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

Zwraca kolekcję zachowań dla efektu. Odczyt/zapis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Zwraca:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

Zwraca kolekcję zachowań dla efektu. Odczyt/zapis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Określa wartość czasu dla efektu. Odczyt/zapis [ITiming](../../com.aspose.slides/itiming).

**Zwraca:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Określa wartość czasu dla efektu. Odczyt/zapis [ITiming](../../com.aspose.slides/itiming).

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

Zdefiniowano wbudowany dźwięk dla efektu. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

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
>          // Pobiera dźwięk efektu jako tablicę bajtów
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

Zdefiniowano wbudowany dźwięk dla efektu. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

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
>          // Pobiera dźwięk efektu jako tablicę bajtów
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

Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Odczyt/zapis  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Pobierz pierwszy efekt drugiego slajdu.
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

Ten atrybut określa, czy efekt animacji zatrzymuje poprzedni dźwięk. Odczyt/zapis  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Pobierz pierwszy efekt drugiego slajdu.
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

Zdefiniowano typ poanimacji dla efektu. Odczyt/zapis  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji po efektu na "Hide on Next Mouse Click"
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

Zdefiniowano typ poanimacji dla efektu. Odczyt/zapis  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień animację po efektu na "Hide on Next Mouse Click"
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

Zdefiniowano kolor po animacji dla efektu. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji po efektu na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ustaw kolor po animacji efektu.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
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

Zdefiniowano kolor po animacji dla efektu. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji po efekcie na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ustaw kolor po animacji efektu.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
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

Określa typ animacji tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub jednocześnie. Odczyt/zapis  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji tekstu efektu na "By letter"
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

Określa typ animacji tekstu dla efektu. Tekst kształtu może być animowany literą, słowem lub jednocześnie. Odczyt/zapis  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji tekstu efektu na "By letter"
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

Określa opóźnienie między częściami animowanego tekstu (słowami lub literami). Pozytywna wartość określa procent czasu trwania efektu. Ujemna wartość określa opóźnienie w sekundach. Odczyt/zapis  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji tekstu efektu na "By word"
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

Określa opóźnienie między częściami animowanego tekstu (słowami lub literami). Pozytywna wartość określa procent czasu trwania efektu. Ujemna wartość określa opóźnienie w sekundach. Odczyt/zapis  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Pobierz pierwszy efekt pierwszego slajdu.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Zmień typ animacji tekstu efektu na "By word"
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