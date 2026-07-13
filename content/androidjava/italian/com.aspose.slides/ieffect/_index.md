---
title: IEffect
second_title: Riferimento API Aspose.Slides per Android tramite Java
description: Rappresenta l'effetto di animazione.
type: docs
url: /it/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Rappresenta l'effetto di animazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSequence()](#getSequence--) | Restituisce una sequenza per un effetto. |
| [getTextAnimation()](#getTextAnimation--) | Restituisce l'animazione del testo. |
| [getPresetClassType()](#getPresetClassType--) | Definisce la classe dell'effetto. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definisce la classe dell'effetto. |
| [getType()](#getType--) | Definisce il tipo dell'effetto. |
| [setType(int value)](#setType-int-) | Definisce il tipo dell'effetto. |
| [getSubtype()](#getSubtype--) | Definisce il sottotipo dell'effetto. |
| [setSubtype(int value)](#setSubtype-int-) | Definisce il sottotipo dell'effetto. |
| [getBehaviors()](#getBehaviors--) | Restituisce la collezione di comportamenti per l'effetto. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Restituisce la collezione di comportamenti per l'effetto. |
| [getTiming()](#getTiming--) | Definisce il valore di temporizzazione per l'effetto. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definisce il valore di temporizzazione per l'effetto. |
| [getTargetShape()](#getTargetShape--) | Restituisce la forma di destinazione per l'effetto. |
| [getSound()](#getSound--) | Definisce il suono incorporato per l'effetto. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definisce il suono incorporato per l'effetto. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definisce un tipo di animazione successiva per l'effetto. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definisce un tipo di animazione successiva per l'effetto. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definisce un colore di animazione successiva per l'effetto. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definisce un colore di animazione successiva per l'effetto. |
| [getAnimateTextType()](#getAnimateTextType--) | Definisce un tipo di animazione del testo per l'effetto. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definisce un tipo di animazione del testo per l'effetto. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definisce un ritardo tra le parti di testo animate (parole o lettere). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definisce un ritardo tra le parti di testo animate (parole o lettere). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Restituisce una sequenza per un effetto. Solo lettura [ISequence](../../com.aspose.slides/isequence).

**Restituisce:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Restituisce l'animazione del testo. Solo lettura [ITextAnimation](../../com.aspose.slides/itextanimation).

**Restituisce:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Definisce la classe dell'effetto. Lettura/Scrittura [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Restituisce:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Definisce la classe dell'effetto. Lettura/Scrittura [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


Definisce il tipo dell'effetto. Lettura/Scrittura [EffectType](../../com.aspose.slides/effecttype).

**Restituisce:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Definisce il tipo dell'effetto. Lettura/Scrittura [EffectType](../../com.aspose.slides/effecttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Definisce il sottotipo dell'effetto. Lettura/Scrittura [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Restituisce:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Definisce il sottotipo dell'effetto. Lettura/Scrittura [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Restituisce la collezione di comportamenti per l'effetto. Lettura/Scrittura [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Restituisce:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Restituisce la collezione di comportamenti per l'effetto. Lettura/Scrittura [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Definisce il valore di temporizzazione per l'effetto. Lettura/Scrittura [ITiming](../../com.aspose.slides/itiming).

**Restituisce:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Definisce il valore di temporizzazione per l'effetto. Lettura/Scrittura [ITiming](../../com.aspose.slides/itiming).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Restituisce la forma di destinazione per l'effetto. Solo lettura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Definisce il suono incorporato per l'effetto. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

--------------------

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
public abstract void setSound(IAudio value)
```


Definisce il suono incorporato per l'effetto. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

--------------------

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Lettura/Scrittura  boolean .

--------------------

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
>          // Cambia il suono del secondo effetto in "Stop Previous Sound"
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
public abstract void setStopPreviousSound(boolean value)
```


Questo attributo specifica se l'effetto di animazione interrompe il suono precedente. Lettura/Scrittura  boolean .

--------------------

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
>          // Cambia il suono del secondo effetto in "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Definisce un tipo di animazione successiva per l'effetto. Lettura/Scrittura  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia l'animazione successiva dell'effetto in "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Definisce un tipo di animazione successiva per l'effetto. Lettura/Scrittura  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia l'animazione successiva dell'effetto in "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Definisce un colore di animazione successiva per l'effetto. Lettura/Scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione successiva dell'effetto a "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Imposta il colore di animazione successiva dell'effetto.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Definisce un colore di animazione successiva per l'effetto. Lettura/Scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione successiva dell'effetto a "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Imposta il colore di animazione successiva dell'effetto.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Lettura/Scrittura  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "Per lettera"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Definisce un tipo di animazione del testo per l'effetto. Il testo della forma può essere animato per lettera, per parola o tutto in una volta. Lettura/Scrittura  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "Per lettera"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell'effetto. Un valore negativo specifica il ritardo in secondi. Lettura/Scrittura  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Imposta il ritardo tra le parti di testo animate al 20% della durata dell'effetto.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Definisce un ritardo tra le parti di testo animate (parole o lettere). Un valore positivo specifica la percentuale della durata dell'effetto. Un valore negativo specifica il ritardo in secondi. Lettura/Scrittura  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Ottiene il primo effetto della prima diapositiva.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Cambia il tipo di animazione del testo dell'effetto in "Per parola"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Imposta il ritardo tra le parti di testo animate al 20% della durata dell'effetto.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |